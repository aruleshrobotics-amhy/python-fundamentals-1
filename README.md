# 🐍 PYTHON FUNDAMENTALS -- COMPLETE MASTER GUIDE(GROUP 1)


------------------------------------------------------------------------

# 1️⃣ Python Comments

## What Are Comments?

Comments are lines in code that Python completely ignores during
execution.

### Why We Use Comments

-   To explain logic
-   To improve readability
-   To help teamwork
-   To debug code
-   To temporarily disable code

### Single-Line Comment

``` python
# This is a single-line comment
print("Hello World")
```

### Multi-Line Comment

Python does not have a true multi-line comment syntax. We use triple
quotes:

``` python
"""
This is a multi-line comment
It spans multiple lines
"""
```

------------------------------------------------------------------------

# 2️⃣ Variables

## What is a Variable?

A variable is a container used to store data.

``` python
name = "Arulesh"
age = 21
```

## Variable Naming Rules

-   Must start with letter or underscore
-   Cannot start with number
-   Cannot use reserved keywords
-   Case-sensitive

## Dynamic Typing

Python automatically detects data type.

``` python
x = 10
x = "Hello"
```

------------------------------------------------------------------------

# 3️⃣ Data Types

Python has several built-in data types.

## Integer (int)

Whole numbers.

``` python
a = 10
```

## Float

Decimal numbers.

``` python
b = 3.14
```

## String (str)

Sequence of characters.

``` python
name = "Python"
```

## Boolean (bool)

True or False.

``` python
is_active = True
```

## List

Ordered, mutable collection.

``` python
numbers = [1, 2, 3]
```

## Tuple

Ordered, immutable collection.

``` python
point = (10, 20)
```

## Set

Unordered, unique elements.

``` python
unique_numbers = {1, 2, 3}
```

## Dictionary

Key-value pairs.

``` python
student = {"name": "Arulesh", "age": 21}
```

------------------------------------------------------------------------

# 4️⃣ Type Casting

Type casting means converting one data type into another.

## String to Integer

``` python
num = int("10")
print(num + 5)
```

## Integer to String

``` python
age = 21
age_str = str(age)
print("Age is " + age_str)
```

## Float to Integer

``` python
x = 3.9
print(int(x))
```

Note: Decimal part is removed (not rounded).

------------------------------------------------------------------------

# 5️⃣ Python Print

## Basic Print

``` python
print("Hello World")
```

## Printing Multiple Values

``` python
print("Age:", 21)
```

## f-Strings (Recommended)

``` python
name = "Arulesh"
age = 21
print(f"My name is {name} and I am {age} years old")
```

------------------------------------------------------------------------

# 6️⃣ Python Strings

Strings are immutable sequences of characters.

## Indexing

``` python
text = "Python"
print(text[0])
print(text[-1])
```

## Slicing

``` python
print(text[0:4])
```

## String Methods

``` python
text = "python programming"
print(text.upper())
print(text.lower())
print(text.capitalize())
print(text.replace("python", "Java"))
print(text.split())
```

## Immutability

Strings cannot be modified after creation.

------------------------------------------------------------------------

# 7️⃣ Lists

Lists are ordered and mutable.

``` python
numbers = [10, 20, 30]
```

## Access Elements

``` python
print(numbers[0])
```

## Modify Elements

``` python
numbers[1] = 50
```

## List Methods

``` python
numbers.append(40)
numbers.insert(1, 15)
numbers.remove(30)
numbers.pop()
numbers.sort()
```

## Loop Through List

``` python
for num in numbers:
    print(num)
```

------------------------------------------------------------------------

# 8️⃣ Tuples

Tuples are ordered but immutable.

``` python
point = (10, 20)
print(point[0])
```

Why use tuples? - Faster than lists - Protect data from modification

------------------------------------------------------------------------

# 9️⃣ Sets

Sets store unique values.

``` python
nums = {1, 2, 3, 3}
print(nums)
```

## Set Operations

``` python
a = {1,2,3}
b = {3,4,5}

print(a.union(b))
print(a.intersection(b))
print(a.difference(b))
```

------------------------------------------------------------------------

# 🔟 Dictionaries

Dictionaries store data in key-value pairs.

``` python
student = {
    "name": "Arulesh",
    "age": 21
}
```

## Access Value

``` python
print(student["name"])
```

## Add or Modify

``` python
student["city"] = "Chennai"
student["age"] = 22
```

## Loop Through Dictionary

``` python
for key, value in student.items():
    print(key, value)
```

------------------------------------------------------------------------

# 1️⃣1️⃣ If Else

Conditional execution.

``` python
age = 18

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

------------------------------------------------------------------------

# 1️⃣2️⃣ If Elif Else

Multiple conditions.

``` python
marks = 85

if marks >= 90:
    print("A")
elif marks >= 75:
    print("B")
else:
    print("C")
```

------------------------------------------------------------------------

# 1️⃣3️⃣ Types of If Branch

## Nested If

``` python
age = 20
citizen = True

if age >= 18:
    if citizen:
        print("Eligible")
```

## Ternary Operator

``` python
age = 20
status = "Adult" if age >= 18 else "Minor"
print(status)
```

------------------------------------------------------------------------

# 1️⃣4️⃣ Switch (match-case)

Available in Python 3.10+

``` python
day = 1

match day:
    case 1:
        print("Monday")
    case 2:
        print("Tuesday")
    case _:
        print("Invalid")
```

------------------------------------------------------------------------

# 1️⃣5️⃣ Loops

## For Loop

``` python
for i in range(5):
    print(i)
```

## While Loop

``` python
count = 0

while count < 5:
    print(count)
    count += 1
```

## Break Statement

``` python
for i in range(5):
    if i == 3:
        break
    print(i)
```

## Continue Statement

``` python
for i in range(5):
    if i == 3:
        continue
    print(i)
```

------------------------------------------------------------------------

# ✅ FINAL SUMMARY

All 15 Python Fundamental topics have been covered in detail:

1.  Comments
2.  Variables
3.  Data Types
4.  Type Casting
5.  Print
6.  Strings
7.  Lists
8.  Tuples
9.  Sets
10. Dictionaries
11. If Else
12. If Elif Else
13. If Branch Types
14. Switch (match-case)
15. Loops

------------------------------------------------------------------------

END OF DOCUMENT
