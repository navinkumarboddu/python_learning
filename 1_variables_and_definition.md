# Python Variable Assignment and Reassignment Example

This repository contains a simple Python script demonstrating variable assignment and reassignment, as well as showcasing some common errors related to variable names.

#### Example Code

```python
>>> print("Hello World!!!")
Hello World!!!
```

### Assigning and Reassigning Variables
```
>>> age = 'Navin'
>>> age
'Navin'

>>> age = 14
>>> age
14

>>> age = 15
>>> age
15

>>> varName = 20
>>> varName
20
```

### Multiple Variable Assignments
```markdown
>>> person1 = 'Abby'
>>> person2 = 'John'

>>> person1, person2, person3 = 'Abby', 'James', 'Lebron'
>>> person3
'Lebron'
```

## Common Errors

### Invalid Variable Names

```markdown
>>> var4 = 'Apples'
>>> var 4 = 'Apples'
  File "<stdin>", line 1
    var 4 = 'Apples'
        ^
SyntaxError: invalid syntax
```

### Incorrect Multiple Assignments
```markdown
>>> var1 = var2 = var3 = 'Apples'
>>> var1 var2 var3 = 'Mangoes'
  File "<stdin>", line 1
    var1 var2 var3 = 'Mangoes'
         ^^^^
SyntaxError: invalid syntax
```

### Correct Multiple Assignments
```markdown
>>> var1 = var2 = var3 = 'Mangoes'
>>> var3
'Mangoes'
```