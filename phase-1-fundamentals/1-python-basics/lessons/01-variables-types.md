# Lesson 1: Variables and Basic Data Types in Python

## Objectives

After this lesson, you will be able to:

- Create and use variables in Python
- Understand Python's basic data types
- Use basic operators
- Print and format output

## 1. Variables in Python

Unlike many other languages, Python variables:

- Don't need to be declared with specific types
- Are created when you first assign a value
- Can change types dynamically

```python
# Creating variables
age = 25        # integer
name = "Alice"  # string
height = 1.75   # float
is_student = True  # boolean

# You can reassign different types
age = "Twenty five"  # This is valid in Python!
```

## 2. Basic Data Types

### Numbers

```python
# Integers
count = 42
negative = -17

# Floats
price = 19.99
pi = 3.14159

# Basic operations
sum = 5 + 3    # Addition
diff = 10 - 4  # Subtraction
prod = 6 * 7   # Multiplication
quot = 15 / 3  # Division (returns float)
int_div = 15 // 3  # Integer division
power = 2 ** 3 # Exponentiation
remainder = 17 % 5  # Modulo (remainder)
```

### Strings

```python
# Creating strings
name = "Bob"
message = 'Hello, World!'
long_text = """This is a
multi-line
string"""

# String operations
greeting = "Hello " + name  # Concatenation
repeated = "Ha" * 3        # Repetition -> "HaHaHa"
length = len(name)         # Length -> 3
```

### Booleans

```python
is_active = True
is_closed = False

# Boolean operations
result1 = True and False  # False
result2 = True or False   # True
result3 = not True       # False
```

## 3. Type Conversion

Python provides functions to convert between types:

```python
# String to number
age_str = "25"
age_num = int(age_str)    # -> 25 (integer)
price_str = "19.99"
price_num = float(price_str)  # -> 19.99 (float)

# Number to string
count = 42
count_str = str(count)    # -> "42"

# Check type
print(type(count))      # -> <class 'int'>
print(type(count_str))  # -> <class 'str'>
```

## 4. Printing and Formatting

### Basic Printing

```python
name = "Alice"
age = 25

# Simple print
print("Hello!")

# Print variables
print(name)
print("Name:", name, "Age:", age)
```

### String Formatting

```python
# f-strings (recommended, Python 3.6+)
print(f"Hello, {name}! You are {age} years old.")

# format() method
print("Hello, {}! You are {} years old.".format(name, age))

# % operator (older style)
print("Hello, %s! You are %d years old." % (name, age))
```

## Practice Exercises

1. Basic Variables

```python
# Create variables for your name, age, and favorite number
# Print them using f-strings
```

2. Type Conversion

```python
# Convert "123.45" to a float
# Then convert it to an integer
# Print both results
```

3. String Operations

```python
# Create two strings and concatenate them
# Print the length of the result
# Create a string and repeat it 3 times
```

## Common Mistakes to Avoid

- Don't use Python keywords as variable names (like `list`, `str`, `int`)
- Remember that string concatenation only works with strings
- Be careful with integer division vs float division
- Watch out for indentation (Python is sensitive to this)

## Challenge

Create a simple temperature converter:

```python
# Write code to:
# 1. Create a variable with a Celsius temperature
# 2. Convert it to Fahrenheit using the formula: F = C * 9/5 + 32
# 3. Print both temperatures using nice formatting
```

## Next Steps

- Try all the exercises in this lesson
- Experiment with different combinations
- Move on to the exercises folder for more practice
- If you're comfortable, proceed to the next lesson on control flow

Remember: The best way to learn is by typing the code yourself and experimenting with it!
