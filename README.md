# 🐍 Python Fundamentals -- Complete Detailed Guide (Group 1)

This README contains a complete in-depth explanation of Python
Fundamentals including detailed concepts and examples.

------------------------------------------------------------------------

# 1️⃣ Python Comments

## What are Comments?

Comments are lines in code that Python ignores.\
They are used to: - Explain logic - Improve readability - Debug code -
Temporarily disable code

### Single Line Comment

``` python
# This is a single-line comment
print("Hello")
```

### Multi-line Comment

``` python
"""
This is a multi-line comment
It can span multiple lines
"""
```

------------------------------------------------------------------------

# 2️⃣ Variables

## What is a Variable?

A variable stores data.

``` python
name = "Arulesh"
age = 21
```

## Variable Naming Rules

-   Can contain letters, numbers, underscores
-   Cannot start with a number
-   Cannot use reserved keywords

``` python
my_name = "Python"   # valid
# 2name = "Wrong"    # invalid
```

## Dynamic Typing

``` python
x = 10
x = "Hello"
```

------------------------------------------------------------------------

# 3️⃣ Data Types

## Integer

``` python
a = 10
```

## Float

``` python
b = 3.14
```

## String

``` python
name = "Python"
```

## Boolean

``` python
is_active = True
```

## List

``` python
numbers = [1, 2, 3]
```

## Tuple

``` python
point = (10, 20)
```

## Set

``` python
unique_numbers = {1, 2, 3}
```

## Dictionary

``` python
student = {"name": "Arulesh", "age": 21}
```

------------------------------------------------------------------------

# 4️⃣ Type Casting

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

------------------------------------------------------------------------

# 5️⃣ Python Print

## Basic Print

``` python
print("Hello World")
```

## Multiple Values

``` python
print("Age:", 21)
```

## f-Strings

``` python
name = "Arulesh"
age = 21
print(f"My name is {name} and I am {age} years old")
```

------------------------------------------------------------------------

# 6️⃣ Python Strings

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

``` python
numbers = [10, 20, 30]
```

## Access

``` python
print(numbers[0])
```

## Modify

``` python
numbers[1] = 50
```

## Methods

``` python
numbers.append(40)
numbers.insert(1, 15)
numbers.remove(30)
numbers.pop()
numbers.sort()
```

## Loop

``` python
for num in numbers:
    print(num)
```

------------------------------------------------------------------------

# 8️⃣ Tuples

``` python
point = (10, 20)
print(point[0])
```

Tuples are immutable.

------------------------------------------------------------------------

# 9️⃣ Sets

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

``` python
student = {
    "name": "Arulesh",
    "age": 21
}
```

## Access

``` python
print(student["name"])
```

## Add / Modify

``` python
student["city"] = "Chennai"
student["age"] = 22
```

## Loop

``` python
for key, value in student.items():
    print(key, value)
```

------------------------------------------------------------------------

# 1️⃣1️⃣ If Else

``` python
age = 18

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

------------------------------------------------------------------------

# 1️⃣2️⃣ If Elif Else

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

## Break Example

``` python
for i in range(5):
    if i == 3:
        break
    print(i)
```

------------------------------------------------------------------------

# ✅ Total Topics Covered: 15
