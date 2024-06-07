---
---

# Lists

Lists are one of the most commonly used data structures in Python. They are ordered, mutable, and allow duplicate elements.

## Creating a list

A list is created by placing all the items (elements) inside square brackets `[]`, separated by commas.

```python
# Creating a list with integers
numbers = [1, 2, 3, 4, 5]

# Creating a list with mixed data types
mixed_list = [1, "Hello", 3.14, True]

# Creating an empty list
empty_list = []
```

## Accessing Elements

You can access elements in a list using their index. Python uses zero-based indexing.

```python
Copy code
# Accessing the first element
first_element = numbers[0]  # Output: 1

# Accessing the last element
last_element = numbers[-1]  # Output: 5
```

## Modifying Elements

You can modify elements in a list by assigning a new value to an index.

```python
Copy code
# Changing the second element
numbers[1] = 20  # Now, numbers is [1, 20, 3, 4, 5]
```

## Adding Elements

You can add elements to a list using the append(), insert(), or extend() methods.

```python
Copy code
# Using append() to add an element at the end
numbers.append(6)  # Now, numbers is [1, 20, 3, 4, 5, 6]

# Using insert() to add an element at a specific index
numbers.insert(1, 10)  # Now, numbers is [1, 10, 20, 3, 4, 5, 6]

# Using extend() to add multiple elements at the end
numbers.extend([7, 8, 9])  # Now, numbers is [1, 10, 20, 3, 4, 5, 6, 7, 8, 9]
```

## Removing Elements

You can remove elements from a list using the remove(), pop(), or del statements.

```python
Copy code
# Using remove() to remove the first occurrence of an element
numbers.remove(10)  # Now, numbers is [1, 20, 3, 4, 5, 6, 7, 8, 9]

# Using pop() to remove an element at a specific index
removed_element = numbers.pop(2)  # Now, numbers is [1, 20, 4, 5, 6, 7, 8, 9] and removed_element is 3

# Using del to delete an element at a specific index
del my_list[0]
```
