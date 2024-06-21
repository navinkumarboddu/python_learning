### Basic if Statement
```
# Define a variable
x = 10

# Basic if statement
if x > 5:
       print("x is greater than 5")
# Explanation: Checks if the value of x is greater than 5. If the condition is true, it prints a message.
```

### if-else Statement
```
# Define a variable
x = 3

# if-else statement
if x > 5:
       print("x is greater than 5")
else:
       print("x is not greater than 5")
# Explanation: Checks if x is greater than 5. If true, it prints the first message. Otherwise, it prints the second message.
```

### if-elif-else Statement
```
# Define a variable
x = 5

# if-elif-else statement
if x > 5:
       print("x is greater than 5")
elif x == 5:
       print("x is equal to 5")
else:
       print("x is less than 5")
# Explanation: Checks multiple conditions. First, if x is greater than 5, it prints the first message. If not, it checks if x is equal to 5 and prints the second message if true. Otherwise, it prints the third message.
```

### Nested if Statements
```
# Define a variable
x = 10
y = 20

# Nested if statements
if x > 5:
       print("x is greater than 5")
if y > 15:
       print("y is also greater than 15")
# Explanation: Checks if x is greater than 5. If true, it prints the first message. Then it checks if y is greater than 15. If both conditions are true, it prints the second message.
```

### Using Logical Operators
```
# Define variables
x = 10
y = 20

# if statement with logical operators
if x > 5 and y > 15:
        print("x is greater than 5 and y is greater than 15")
# Explanation: Uses the 'and' logical operator to check if both conditions are true. If they are, it prints the message.

if x > 5 or y > 25:
        print("Either x is greater than 5 or y is greater than 25")
# Explanation: Uses the 'or' logical operator to check if at least one of the conditions is true. If either condition is true, it prints the message.
```

### if Statements with not
```
# Define a variable
x = False

# if statement with not
if not x:
       print("x is False")
# Explanation: The 'not' operator inverts the boolean value. If x is False, 'not x' becomes True, and it prints the message.
```