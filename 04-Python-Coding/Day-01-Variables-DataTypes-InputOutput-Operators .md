# Day 1 - Python Basics
## TCS Ignite Coding Preparation (30-Day Roadmap)

> Goal: Build a strong programming foundation before solving coding problems.

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand what programming is.
- Write your first Python program.
- Take input from the user.
- Print output.
- Store values using variables.
- Understand different data types.
- Perform calculations using operators.
- Solve beginner coding problems.

---

# What is Programming?

Programming is the process of giving instructions to a computer.

Think of it like giving instructions to a robot.

Example:

You tell your friend:

1. Go to kitchen
2. Take a glass
3. Fill water
4. Bring it back

Similarly,

Computer needs instructions in a programming language.

Python is one such language.

---

# Why Python?

Python is:

- Easy to learn
- Easy to read
- Used by Google
- Used by Netflix
- Used by NASA
- Used in AI
- Used in Data Science
- Used in Web Development

Python is one of the best languages for placement coding.

---

# Your First Program

```python
print("Hello World")
```

Output

```
Hello World
```

The print() function displays output on the screen.

---

# Comments

Comments are ignored by Python.

```python
# This is a comment

print("Hello")
```

---

# Variables

Variables store information.

Real Life Example

Imagine you have boxes.

One box stores books.

One box stores clothes.

One box stores money.

Variable works exactly like a storage box.

Example

```python
name = "Rahul"
age = 20
marks = 88
```

---

# Naming Rules

Correct

```python
student_name
age
totalMarks
```

Wrong

```python
1name
student-name
class
```

---

# Data Types

Python stores different kinds of data.

## Integer

Whole numbers

```python
age = 20
```

---

## Float

Decimal numbers

```python
price = 99.99
```

---

## String

Text

```python
name = "Rahul"
```

---

## Boolean

True or False

```python
is_pass = True
```

---

# Checking Data Type

```python
age = 20

print(type(age))
```

Output

```
<class 'int'>
```

---

# Taking Input

```python
name = input("Enter name: ")

print(name)
```

---

Input

```
Rahul
```

Output

```
Rahul
```

---

# Integer Input

```python
age = int(input("Enter age: "))

print(age)
```

---

# Float Input

```python
salary = float(input("Salary: "))
```

---

# Multiple Inputs

```python
a, b = map(int, input().split())

print(a)
print(b)
```

Input

```
10 20
```

Output

```
10
20
```

---

# Output Formatting

```python
name = "Rahul"

print("Hello", name)
```

Output

```
Hello Rahul
```

---

Using f-string

```python
age = 20

print(f"My age is {age}")
```

Output

```
My age is 20
```

---

# Operators

## Arithmetic Operators

Addition

```python
5 + 2
```

Subtraction

```python
5 - 2
```

Multiplication

```python
5 * 2
```

Division

```python
5 / 2
```

Floor Division

```python
5 // 2
```

Modulus

```python
5 % 2
```

Power

```python
5 ** 2
```

---

# Comparison Operators

```python
>

<

>=

<=

==

!=
```

Example

```python
print(5 > 2)
```

Output

```
True
```

---

# Logical Operators

AND

```python
and
```

OR

```python
or
```

NOT

```python
not
```

---

# Assignment Operators

```python
=

+=

-=

*=

/=
```

---

# Type Casting

Convert one data type into another.

```python
age = "20"

age = int(age)

print(age)
```

---

# Mini Project

Take name and age from user.

Display

```
Hello Rahul

You are 20 years old.
```

Example

```python
name = input("Enter Name: ")
age = int(input("Enter Age: "))

print(f"Hello {name}")
print(f"You are {age} years old.")
```

---

# Common Beginner Mistakes

❌ Forgetting int()

```python
age = input()
```

Correct

```python
age = int(input())
```

---

❌ Using = instead of ==

Wrong

```python
if age = 20
```

Correct

```python
if age == 20
```

---

# Interview Questions

1. What is Python?
2. Why is Python popular?
3. What is a variable?
4. Difference between int and float?
5. Difference between input() and print()?
6. What is type casting?
7. Difference between == and = ?
8. What is modulus operator?
9. What is floor division?
10. What are Boolean values?

---

# Key Takeaways

✔ Variables store values.

✔ Python has different data types.

✔ input() accepts user input.

✔ print() displays output.

✔ Operators perform calculations.

✔ Type casting converts one type into another.

---

# Tomorrow

Day 2

Conditional Statements

- if
- if else
- elif
- Nested if
- TCS Beginner Problems