# Day 1 — Python Fundamentals

Today I started my AI/ML learning journey by going back to the basics of Python.

Before moving into libraries like NumPy, Pandas, and Machine Learning frameworks, I wanted to make sure that my Python fundamentals are clear.

## What I Learned

Today I covered the following basic Python concepts:

### 1. Input and Output

I learned how Python takes input from the user using `input()` and displays information using `print()`.

```python
name = input("Enter your name: ")
print("Hello", name)
```

This helped me understand how a Python program can interact with the user.

Reference: [Input and Output in Python](https://www.geeksforgeeks.org/python/input-and-output-in-python/)

### 2. Variables

I learned how variables are used to store values in Python.

```python
name = "Darshan"
age = 20
```

Python does not require me to explicitly mention the data type while creating a variable.

Reference: [Python Variables](https://www.geeksforgeeks.org/python/python-variables/)

### 3. Keywords

I learned about Python keywords. These are reserved words that have a special meaning in Python and cannot be used as normal variable names.

Some examples are:

```text
if
else
for
while
def
class
return
import
True
False
None
```

Reference: [Python Keywords](https://www.geeksforgeeks.org/python/python-keywords/)

### 4. Data Types

I learned about the basic data types available in Python and how different types of values are stored.

Some of the important ones I covered are:

* `int` — Integer values
* `float` — Decimal values
* `str` — Text
* `bool` — True or False
* `list` — Collection of values
* `tuple` — Ordered, immutable collection
* `set` — Unordered collection of unique values
* `dict` — Collection of key-value pairs

Reference: [Python Data Types](https://www.geeksforgeeks.org/python/python-data-types/)

### 5. Strings

I learned how strings are used to work with text in Python.

```python
name = "Darshan"

print(name)
print(name[0])
print(len(name))
```

I also started understanding basic string operations and indexing.

Reference: [Python String](https://www.geeksforgeeks.org/python/python-string/)

### 6. Lists

I learned about lists, which are used to store multiple values in a single variable.

```python
languages = ["Python", "Java", "C++"]

print(languages[0])
```

Lists are ordered and can be modified after they are created.

Reference: [Python Lists](https://www.geeksforgeeks.org/python/python-lists/)

### 7. Dictionaries

I learned about dictionaries and how they store data in **key-value pairs**.

```python
student = {
    "name": "Darshan",
    "age": 20,
    "branch": "AI/ML"
}

print(student["name"])
```

I understood that dictionaries are useful when I want to associate a value with a specific key.

Reference: [Python Dictionary](https://www.geeksforgeeks.org/python/python-dictionary/)

### 8. Tuples

I learned about tuples and how they are similar to lists, but their values cannot be changed after creation.

```python
coordinates = (10, 20)
print(coordinates)
```

Reference: [Python Tuples](https://www.geeksforgeeks.org/python/python-tuples/)

### 9. Sets

I learned about sets and how they store unique values.

```python
numbers = {1, 2, 3, 3, 4}

print(numbers)
```

The duplicate `3` is automatically removed because sets only contain unique elements.

Reference: [Sets in Python](https://www.geeksforgeeks.org/python/sets-in-python/)

## What I Understood Today

Today was mainly about getting comfortable with the basic building blocks of Python.

I learned how to take input, display output, store values using variables, work with different data types, and use Python's main collection types like lists, dictionaries, tuples, and sets.

These are basic concepts, but I know they are going to be important as I move towards NumPy, Pandas, Machine Learning, and eventually AI/ML projects.

## Day 1 Status

**Python Fundamentals — Started ✅**

Next, I'll continue building my Python fundamentals and gradually move towards the Python concepts that are more useful for AI/ML.
