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

### Nested if-else Statements

```
age = 14
# Assigns the value 14 to the variable 'age'.

if age > 13:
        print("You are eligible for facebook")
You are eligible for facebook
# Explanation: Checks if 'age' is greater than 13. Since 14 is greater than 13, it prints "You are eligible for facebook".
```

### Identation Issues
```
name = "Bob"
# Assigns the value "Bob" to the variable 'name'.

if age > 13:
        if name == "Bob":
            print("You get special privileges")
File "<stdin>", line 3
print("You get special privileges")
TabError: inconsistent use of tabs and spaces in indentation
# Explanation: Checks if 'age' is greater than 13. If true, it further checks if 'name' is "Bob".
# There is a TabError because of inconsistent use of tabs and spaces for indentation.
```

```
if age > 13:
        if name == "Bob":
                print("You get special privileges")
        else:
                print("You are eligible for facebook")
You get special privileges
# Explanation:
# 1. Checks if 'age' is greater than 13. Since 14 is greater than 13, it enters the first if block.
# 2. Inside the first if block, it checks if 'name' is "Bob". Since 'name' is "Bob", it prints "You get special privileges".
# 3. If 'name' was not "Bob", it would print "You are eligible for facebook" from the else block.
```

### Explanation of the Corrected Code Block

```
if age > 13:
     if name == "Bob":
         print("You get special privileges")
     else:
         print("You are eligible for facebook")
You get special privileges

####Step 1: if age > 13:
        This line checks if the variable age is greater than 13. Since age is 14, the condition is true, and it proceeds to the next line.

####Step 2: if name == "Bob":
        This line checks if the variable name is equal to "Bob". Since name is "Bob", the condition is true, and it proceeds to the next line.

####Step 3: print("You get special privileges")
        This line is executed because the nested if condition is true. It prints "You get special privileges".

####Step 4: else:
        This line is part of the nested if-else structure. If the condition name == "Bob" was false, it would proceed to the else block.

####Step 5: print("You are eligible for facebook")
        This line would be executed if the condition name == "Bob" was false. It prints "You are eligible for facebook".

By ensuring consistent indentation, the nested if-else statement works correctly and avoids indentation errors.
```

### if-elif-else Statement

```
>>> day = "Monday"
# Assigns the value "Monday" to the variable 'day'.

if day == "Tuesday":
...     print("Sunny")
... elif day == "Monday":
...     print("Cloudy")
... else:
...     print("Rainy")
... 
Cloudy

#### Step 1: if day == "Tuesday":

    This line checks if the variable day is equal to "Tuesday". Since day is "Monday", the condition is false.

#### Step 2: elif day == "Monday":

    Since the if condition is false, it checks this elif condition. It checks if the variable day is equal to "Monday". Since day is "Monday", the condition is true.

#### Step 3: print("Cloudy")

    This line is executed because the elif condition is true. It prints "Cloudy".

#### Step 4: else:

    This line would be part of the if-elif-else structure. If both the if and elif conditions were false, it would proceed to the else block.

#### Step 5: print("Rainy")

    This line would be executed if both the if and elif conditions were false. It prints "Rainy".

```

### Logical Operator **and**
```
age = 14
# Assigns the value 14 to the variable 'age'.

if age > 13:
     print("You are eligible for facebook")
You are eligible for facebook
# Explanation:
# 1. Checks if 'age' is greater than 13. Since 14 is greater than 13, the condition is true.
# 2. It prints "You are eligible for facebook" because the condition is true.

name = "Bujji"
# Assigns the value "Bujji" to the variable 'name'.

if age > 13 and name == "Bujji":
     print("You are eligible for facebook")
You are eligible for facebook
# Explanation:
# 1. Checks two conditions using the `and` operator:
#    - Checks if 'age' is greater than 13 (True).
#    - Checks if 'name' is equal to "Bujji" (True).
# 2. Both conditions are true, so it prints "You are eligible for facebook".
```