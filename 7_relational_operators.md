# Relational Operators in Python

Relational operators are used to compare values. They evaluate to either `True` or `False`. Here are the main relational operators in Python:

1. **Greater than (`>`)**
2. **Less than (`<`)**
3. **Greater than or equal to (`>=`)**
4. **Less than or equal to (`<=`)**
5. **Equal to (`==`)**
6. **Not equal to (`!=`)**

## Examples and Explanations

### Greater Than (`>`)

The `>` operator checks if the value on the left is greater than the value on the right.

```python
>>> if 5 > 2:
...     print("Hello")
... 
Hello
# Explanation: 5 is greater than 2, so the condition is True and "Hello" is printed.

>>> 6 > 3
True
# Explanation: 6 is greater than 3, so the result is True.

>>> 3 > 7
False
# Explanation: 3 is not greater than 7, so the result is False.
```

### Less Than (<)

The < operator checks if the value on the left is less than the value on the right.

```
>>> 3 < 7
True
# Explanation: 3 is less than 7, so the result is True.

>>> 3 < 1
False
# Explanation: 3 is not less than 1, so the result is False.
```

### Greater Than or Equal To (>=)

The >= operator checks if the value on the left is greater than or equal to the value on the right.

```
>>> 4 >= 4
True
# Explanation: 4 is equal to 4, so the result is True.

>>> 5 <= 6
True
# Explanation: 5 is less than 6, so the result is True.

>>> 5 <= 5
True
# Explanation: 5 is equal to 5, so the result is True.
```

### Equal To (==)

The == operator checks if the value on the left is equal to the value on the right.

```
>>> if 5 == 5:
...     print("Hello")
... 
Hello
# Explanation: 5 is equal to 5, so the condition is True and "Hello" is printed.
```

### Common Error: Using = Instead of ==

Using a single equal sign (=) in an if statement is a common mistake. The = operator is used for assignment, not comparison.

```
>>> if 5 = 5:
  File "<stdin>", line 1
    if 5 = 5:
       ^
SyntaxError: cannot assign to literal here. Maybe you meant '==' instead of '='?
# Explanation: Using `=` for comparison causes a syntax error. The correct operator is `==`.
```

### Not Equal To (!=)

The != operator checks if the value on the left is not equal to the value on the right.

```
>>> 4 != 6
True
# Explanation: 4 is not equal to 6, so the result is True.

>>> 4 != 4
False
# Explanation: 4 is equal to 4, so the result is False.
```

### Additional Examples

```
>>> apple = 5
# Assigns the value 5 to the variable apple.

>>> 4 > 3
True
# Explanation: 4 is greater than 3, so the result is True.

>>> 2 < 5
True
# Explanation: 2 is less than 5, so the result is True.

>>> 7 >= 8
False
# Explanation: 7 is not greater than or equal to 8, so the result is False.

>>> 9 <= 9
True
# Explanation: 9 is equal to 9, so the result is True.

>>> 10 == 10
True
# Explanation: 10 is equal to 10, so the result is True.

>>> 8 != 8
False
# Explanation: 8 is equal to 8, so the result is False.
```

### Common Pitfalls

    Using = instead of ==: Remember, = is for assignment, while == is for comparison.
    Indentation Errors: Python requires proper indentation for blocks of code within if statements.

```
>>> if 5 == 5:
... print("Hello")
  File "<stdin>", line 2
    print("Hello")
    ^
IndentationError: expected an indented block
# Explanation: Indentation is required after the if statement to form a block.
```

### Correcting Indentation

```
>>> if 5 == 5:
...     print("Hello")
... 
Hello
# Explanation: Proper indentation ensures the code block runs correctly.

By understanding and using relational operators correctly, you can effectively control the flow of your Python programs based on conditions.
```