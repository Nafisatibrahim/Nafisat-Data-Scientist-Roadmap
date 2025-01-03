
# Week 1: Introduction to Python

## Overview
Python is a versatile and beginner-friendly programming language widely used in data science for its simplicity and extensive library support. This week, we'll cover Python fundamentals and write a program to calculate basic statistics.

---

## Basics of Python Programming

### Variables and Data Types
**Variables** are used to store data in Python. A variable can hold different types of data.

**Common Data Types:**
- **Integers (`int`)**: Whole numbers, e.g., `5`, `-3`
- **Floats (`float`)**: Decimal numbers, e.g., `3.14`, `-0.01`
- **Strings (`str`)**: Text, e.g., `"Hello, World!"`
- **Booleans (`bool`)**: `True` or `False`

```python
# Example: Variables and Data Types
name = "Nafisat"
age = 25
is_learning = True

print(f"My name is {name}, I'm {age} years old, and it's {is_learning} that I'm learning Python.")
```
**Output:**
```
My name is Nafisat, I'm 25 years old, and it's True that I'm learning Python.
```

---

### Loops
**Loops** allow us to execute a block of code multiple times.

**Types of Loops:**
1. **`for` Loop**: Iterates over a sequence (like a list or range).
2. **`while` Loop**: Continues as long as a condition is true.

```python
# For loop example
for i in range(3):
    print(f"This is iteration {i}")
```
**Output:**
```
This is iteration 0
This is iteration 1
This is iteration 2
```

```python
# While loop example
counter = 0
while counter < 3:
    print(f"Counter is {counter}")
    counter += 1
```
**Output:**
```
Counter is 0
Counter is 1
Counter is 2
```

---

### Functions
**Functions** are reusable blocks of code that perform specific tasks.

**Defining a Function:**
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Nafisat"))
```
**Output:**
```
Hello, Nafisat!
```

**Practice: Write a function to calculate the mean of a list of numbers.**
```python
def calculate_mean(numbers):
    return sum(numbers) / len(numbers)

data = [10, 20, 30, 40, 50]
print(f"The mean is {calculate_mean(data)}")
```
**Output:**
```
The mean is 30.0
```

---

## Practice Task: Basic Statistics
Write a Python program to calculate the mean and median of a list of numbers using the `statistics` module.

```python
import statistics

data = [10, 20, 30, 40, 50]

# Calculate mean
mean = statistics.mean(data)

# Calculate median
median = statistics.median(data)

print(f"Data: {data}")
print(f"Mean: {mean}")
print(f"Median: {median}")
```
**Output:**
```
Data: [10, 20, 30, 40, 50]
Mean: 30
Median: 30
```

---

## Summary
This week, we covered:
- Variables and data types
- Loops (`for` and `while`)
- Functions and how to define them
- Writing a Python program to calculate basic statistics

By completing this week, you've built a solid foundation in Python programming, which is essential for data science tasks.
