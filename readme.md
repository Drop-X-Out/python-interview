# 📚 Python Interview Questions

## 1. What is Python?
Python is a high-level, interpreted, general-purpose programming language. As a general-purpose language, it can be used to build almost any application with the correct tools/libraries. Additionally, Python supports objects, modules, threads, exception-handling, and automatic memory management, which help in modelling real-world problems and building applications to solve these problems.

## 2. Explain how Python is an interpreted language.
Any programming language that is not in machine-level code before runtime is called an interpreted language. Python is thus an interpreted language.

## 3. What type of language is Python?
Although Python can be used to write scripts, it is primarily used as a general-purpose programming language.

## 4. What are the essential features of Python?
- Python is a scripting language. Unlike other programming languages like C and its derivatives, Python does not require compilation before execution.
- Python is dynamically typed, which means you don't have to specify the kinds of variables when declaring them or anything.
- Python is well suited to object-oriented programming since it supports class definition, composition, and inheritance.

## 5. What are built-in types of Python?
Given below are the built-in types of Python:
- Built-in functions
- Boolean
- String
- Complex numbers
- Floating point
- Integers

## 6. What are Python libraries?
A Python library is a group of Python packages. Numpy, Pandas, Matplotlib, Scikit-learn, and many other Python libraries are widely used.

## 7. What Does the `//` Operator Do?
In Python, the `/` operator performs division and returns the quotient in float.
- Example: `5 / 2` returns `2.5`
The `//` operator, on the other hand, returns the quotient in integer.
- Example: `5 // 2` returns `2`

## 8. What are keywords in Python?
In Python, keywords are reserved words with a specific meaning. They are commonly used to specify the type of variables. Variable and function names cannot contain keywords. Following are the 33 keywords of Python:
- Yield
- For
- Else
- Elif
- If
- Not
- Or
- And
- Raise
- Nonlocal
- None
- Is
- In
- Import
- Global
- From
- Finally
- Except
- Del
- Continue
- Class
- Assert
- With
- Try
- False
- True
- Return
- Pass
- Lambda
- Def
- As
- Break
- While

## 9. What is Google Colab?
Google Colab is a free cloud-based platform provided by Google for developing and running machine learning algorithms using Python. It allows users to write and execute Python code, store and share notebooks, and access powerful computing resources, including GPUs and TPUs.

## 10. What is a notebook in Google Colab?
A notebook in Google Colab is a web-based interface that allows users to write and execute Python code and store and share their work. Notebooks can include code, text, images, and other multimedia elements, making them a powerful tool for data analysis and machine learning. Notebooks can be saved to Google Drive or downloaded for offline use.

## 11. What is a Dictionary in Python?
A dictionary is one of Python's built-in data types. It establishes a one-to-one correspondence between keys and values. Dictionary keys and values are stored in pairs in dictionaries. Keys are used to index dictionaries.

## 12. What is the difference between lists and tuples in Python?
| List | Tuple |
| --- | --- |
| Lists are mutable i.e, they can be edited. | Tuples are immutable (tuples are lists that can’t be edited). |
| Lists are slower than tuples. | Tuples are faster than lists. |
| Syntax: `list_1 = [10, ‘Chelsea’, 20]` | Syntax: `tup_1 = (10, ‘Chelsea’, 20)` |

## 13. What is slicing in Python?
Slicing is a technique for accessing specific bits of sequences such as strings, tuples, and lists.

## 14. How to use the slicing operator in Python?
Slicing is a technique for accessing specific bits of sequences such as lists, tuples, and strings. The slicing syntax is `[start:end:step]`. This step can also be skipped. `[start:end]` returns all sequence items from the start (inclusive) to the end-1 element. It means the ith element from the end of the start or end element is negative i. The step represents the jump or the number of components that must be skipped.

## 15. What are negative indexes and why are they used?
The indexes from the end of the list, tuple, or string are called negative indexes.
- `Arr[-1]` denotes the array's last element.

## 16. What does `[::-1]` do?
`[::-1]` is used to reverse the order of an array or a sequence.
```python
import array as arr
My_Array=arr.array('i',[1,2,3,4,5])
My_Array[::-1]
```

## 17. What does `len()` do?
The `len()` function in Python returns the length (the number of items) of an object. The object can be a sequence (such as a string, list, or tuple) or a collection (such as a dictionary).
```python
stg = 'ABCD'
print(len(stg))  # Output: 4
```

## 18. What are Mutable data types?
Mutable data types in Python are those whose value can be changed after they are created. Examples include:
- List
- Dictionary
- Set

## 19. What are Immutable data types?
Immutable data types in Python are those whose value cannot be changed after they are created. Examples include:
- Number (int, float, complex)
- String
- Tuple

## 20. How will you reverse a list in Python?
The `list.reverse()` method reverses the objects of a list in place.
```python
my_list = [1, 2, 3, 4, 5]
my_list.reverse()
print(my_list)  # Output: [5, 4, 3, 2, 1]
```
## 21. What is indexing in Python?
Indexing in Python refers to accessing individual elements of a sequence (such as a string, list, or tuple) by their position in the sequence. In Python, indexing starts at 0, so the first element of a sequence has an index of 0, the second element has an index of 1, and so on.

## 22. How do you index a list in Python?
To index a list in Python, you use square brackets `[]` with the index of the element you want to access. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[0])  # Output: 10
print(my_list[2])  # Output: 30
```

## 23. What is slicing in Python?
Slicing in Python is a technique for accessing a portion of a sequence (such as a string, list, or tuple) by specifying a range of indices. The syntax for slicing is `sequence[start:end]`, where `start` is the index of the first element to include and `end` is the index of the first element to exclude.
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[1:4])  # Output: [20, 30, 40]
```

## 24. How do you slice a list in Python?
To slice a list in Python, you use the same square bracket notation as for indexing, but you specify a range of indices instead of a single index. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[1:4])  # Output: [20, 30, 40]
```

## 25. Can you specify a step size when slicing a list in Python?
Yes, you can specify a step size using the syntax `sequence[start:end:step]`. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[0:5:2])  # Output: [10, 30, 50]
```

## 26. What happens if you specify an index that is out of range when indexing or slicing a sequence in Python?
If you specify an index that is out of range when indexing or slicing a sequence in Python, it raises an `IndexError` exception. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[5])  # IndexError: list index out of range
```

## 27. What is negative indexing in Python?
Negative indexing in Python allows you to access elements from the end of a sequence using negative indices. `-1` refers to the last element, `-2` refers to the second last element, and so on. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[-1])  # Output: 50
print(my_list[-2])  # Output: 40
```

## 28. How do you use negative indexing to access list elements in Python?
To use negative indexing to access elements of a list in Python, you use negative indices inside square brackets `[]`. Negative indices count from the end of the list, with `-1` referring to the last element, `-2` to the second last element, and so forth. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[-1])  # Output: 50
print(my_list[-2])  # Output: 40
```

## 29. Can you use slicing to modify a list in Python?
Yes, you can use slicing to modify a list in Python by assigning a new sequence to the sliced portion of the list. For example:
```python
my_list = [1, 2, 3, 4, 5]
my_list[1:4] = [6, 7, 8]  # Replace elements from index 1 to 3 with [6, 7, 8]
print(my_list)  # Output: [1, 6, 7, 8, 5]
```

## 30. What happens if you slice a sequence with a start index that is greater than the end index?
If you slice a sequence with a start index that is greater than the end index, you will get an empty sequence. For example:
```python
my_list = [10, 20, 30, 40, 50]
print(my_list[3:1])  # Output: []
```

## 31. What is an operator in Python?
An operator in Python is a symbol or sequence of symbols that performs an operation on one or more operands. Examples of operators in Python include arithmetic, comparison, logical, and assignment operators.

## 32. How are arithmetic operators used in Python?
Arithmetic operators in Python are used to perform mathematical operations on numeric data types such as integers and floating-point numbers. Examples of arithmetic operators in Python include `+` (addition), `-` (subtraction), `*` (multiplication), `/` (division), `%` (modulus), and `**` (exponentiation).

```python
# Example of arithmetic operators
a = 10
b = 3
print(a + b)  # Output: 13
print(a - b)  # Output: 7
print(a * b)  # Output: 30
print(a / b)  # Output: 3.3333333333333335
print(a % b)  # Output: 1
print(a ** b) # Output: 1000
```

## 32. How are arithmetic operators used in Python?
Arithmetic operators in Python are used to perform mathematical operations on numeric data types such as integers and floating-point numbers. Here are examples of arithmetic operators in Python:

- **Addition (`+`)**: Adds two operands.
- **Subtraction (`-`)**: Subtracts the right operand from the left operand.
- **Multiplication (`*`)**: Multiplies two operands.
- **Division (`/`)**: Divides the left operand by the right operand, resulting in a float.
- **Modulus (`%`)**: Returns the remainder when the left operand is divided by the right operand.
- **Exponentiation (`**`)**: Performs exponential (power) calculation on operators.

Examples:
```python
a = 10
b = 3

print(a + b)    # Output: 13
print(a - b)    # Output: 7
print(a * b)    # Output: 30
print(a / b)    # Output: 3.3333333333333335
print(a % b)    # Output: 1
print(a ** b)   # Output: 1000
```

## 33. How are comparison operators used in Python?
Comparison operators in Python are used to compare two values and return a Boolean value indicating whether the comparison is true or false. Here are examples of comparison operators in Python:

- **Equal to (`==`)**: Returns True if the operands are equal.
- **Not equal to (`!=`)**: Returns True if the operands are not equal.
- **Greater than (`>`)**: Returns True if the left operand is greater than the right operand.
- **Less than (`<`)**: Returns True if the left operand is less than the right operand.
- **Greater than or equal to (`>=`)**: Returns True if the left operand is greater than or equal to the right operand.
- **Less than or equal to (`<=`)**: Returns True if the left operand is less than or equal to the right operand.

Examples:
```python
x = 10
y = 5

print(x == y)   # Output: False
print(x != y)   # Output: True
print(x > y)    # Output: True
print(x < y)    # Output: False
print(x >= y)   # Output: True
print(x <= y)   # Output: False
```

## 34. How are logical operators used in Python?
Logical operators in Python are used to combine Boolean expressions and return a Boolean value indicating the result of the combination. Here are the logical operators in Python:

- **Logical AND (`and`)**: Returns True if both operands are true.
- **Logical OR (`or`)**: Returns True if either of the operands is true.
- **Logical NOT (`not`)**: Returns True if the operand is false (complements the operand).

Examples:
```python
p = True
q = False

print(p and q)   # Output: False
print(p or q)    # Output: True
print(not p)     # Output: False
```

## 35. What is the difference between `/` and `//` operators in Python?
The `/` operator performs floating-point division, while the `//` operator performs integer division (also known as floor division). Here's an example:

```python
print(5 / 2)     # Output: 2.5
print(5 // 2)    # Output: 2
```

## 36. What is the difference between `=` and `==` operators in Python?
The `=` operator is used for assignment, while the `==` operator is used for comparison. Examples:

```python
x = 5     # Assigns the value 5 to variable x
y = 10    # Assigns the value 10 to variable y

print(x == y)   # Output: False (because x is not equal to y)
```

## 37. What are the bitwise operators in Python, and how are they used?
Bitwise operators in Python manipulate numbers on a bit-level. Here are the bitwise operators:

- **Bitwise AND (`&`)**: Sets each bit to 1 if both bits are 1.
- **Bitwise OR (`|`)**: Sets each bit to 1 if at least one of the bits is 1.
- **Bitwise XOR (`^`)**: Sets each bit to 1 if only one of the bits is 1.
- **Bitwise NOT (`~`)**: Inverts all the bits of a number.

Examples:
```python
a = 10    # Binary: 1010
b = 5     # Binary: 0101

# Bitwise AND
print(a & b)    # Output: 0 (Binary: 0000)

# Bitwise OR
print(a | b)    # Output: 15 (Binary: 1111)

# Bitwise XOR
print(a ^ b)    # Output: 15 (Binary: 1111)

# Bitwise NOT
print(~a)       # Output: -11 (Binary: ...1111111111111111110101)
```

## 38. What are membership operators in Python?
Membership operators are used to test whether a value or variable is found in a sequence (string, list, tuple, set, dictionary). Here are the membership operators in Python:

- **`in`**: Returns True if a value exists in the sequence.
- **`not in`**: Returns True if a value does not exist in the sequence.

Examples:
```python
my_list = [1, 2, 3, 4, 5]

print(3 in my_list)     # Output: True
print(6 in my_list)     # Output: False

print(3 not in my_list) # Output: False
print(6 not in my_list) # Output: True
```

## 39. How does the `in` operator work in Python?
The `in` operator tests whether a value exists in a sequence. It returns True if the value is found in the sequence and False otherwise.

Example:
```python
my_list = [1, 2, 3, 4, 5]

print(3 in my_list)     # Output: True
print(6 in my_list)     # Output: False

print(3 not in my_list) # Output: False
print(6 not in my_list) # Output: True
```

## 40. What are identity operators in Python?
Identity operators compare the memory locations of two objects. Here are the identity operators in Python:

- **`is`**: Returns True if both variables point to the same object.
- **`is not`**: Returns True if both variables do not point to the same object.

Examples:
```python
x = [1, 2, 3]
y = [1, 2, 3]
z = x

print(x is z)     # Output: True (because both x and z point to the same object)
print(x is y)     # Output: False (because x and y point to different objects)
print(x is not y) # Output: True (because x and y point to different objects)
```

## 41. What are inbuilt functions in Python?
Inbuilt functions in Python are pre-defined functions that are available for use without needing to be imported. They are built into the Python interpreter. Examples include `print()`, `len()`, `max()`, `min()`, `sum()`, etc.

Example:
```python
numbers = [1, 2, 3, 4, 5]

print(len(numbers))    # Output: 5
print(max(numbers))    # Output: 5
print(min(numbers))    # Output: 1
print(sum(numbers))    # Output: 15
```

## 42. Give an example of an inbuilt function in Python.
An example of an inbuilt function is the `print()` function, which is used to output data to the console. Another example is the `len()` function, which returns the length of a sequence.

Example:
```python
text = "Hello, World!"
print(text)          # Output: Hello, World!

numbers = [1, 2, 3, 4, 5]
print(len(numbers))  # Output: 5
```

## 43. What are user-defined functions in Python?
User-defined functions in Python are functions defined by the user to perform a specific task. They are created using the `def` keyword, followed by the function name and parameters (if any). Example:

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")   # Output: Hello, Alice!
greet("Bob")     # Output: Hello, Bob!
```

## 44. How are arguments passed to functions in Python?
Arguments can be passed to functions in Python in several ways:

- **Positional arguments**: These are arguments passed based on their position in the function definition.
- **Keyword arguments**: These are arguments identified by parameter names.
- **Default arguments**: These are arguments that take a default value if no argument is provided.
- **Variable-length arguments**: These are arguments that allow the function to accept any number of arguments.

Examples:
```python
# Positional arguments
def greet(name, message):
    print(f"{message}, {name}!")

greet("Alice", "Hello")   # Output: Hello, Alice!

# Keyword arguments
def introduce(first_name, last_name):
    print(f"My name is {first_name} {last_name}.")

introduce(last_name="Smith", first_name="John")   # Output: My name is John Smith.

# Default arguments
def greet_default(name, message="Hello"):
    print(f"{message}, {name}!")

greet_default("Alice")                      # Output: Hello, Alice!
greet_default("Bob", "Good morning")        # Output: Good morning, Bob!

# Variable-length arguments (*args)
def sum_numbers(*args):
    total = 0
    for num in args:
        total += num
    return total

print(sum_numbers(1, 2, 3, 4, 5))   # Output: 15
```

## 45. What is the difference between arguments and parameters in Python?
In Python functions:
- **Parameters** are names listed in the function definition.
- **Arguments** are the values passed to the function when calling it.

Example:
```python
def greet(name, message):
    print(f"{message}, {name}!")

greet("Alice", "Hello")   # "Alice" and "Hello" are arguments
```

# MORE COMING SOON ....


