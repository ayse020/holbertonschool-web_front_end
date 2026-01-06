![Python Objects Diagram](https://www.python.org/static/community_logos/python-logo.png)

### Introduction
In learning Python, we understand that "everything is an object." This includes not just the values we use, but also the ways in which we manipulate and interact with these values. This project delves deeply into the concepts of mutability and immutability, showcasing how Python handles data types and how these characteristics affect programming practices.

### ID and Type
In Python, you can identify the type of an object using the type() function and its memory location (ID) using the id() function.

```python
a = 5
print(type(a))  # <class 'int'>
print(id(a))
b = [1, 2, 3]
print(type(b))  # <class 'list'>
print(id(b))
