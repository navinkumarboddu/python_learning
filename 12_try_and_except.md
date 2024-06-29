### 1. try anc except block

```
try:
    if name > 3:
        print("Hi")
except:
    print("Python ran into an error. Please take a look at your code again.")
```

Explanation:
* The **try** block contains the code that might cause an error.
* The statement if name > 3: is checked.
* If name is greater than 3, it will print "Hi".
* If name is not defined or if there is a type error (e.g., comparing a string with an integer), an error will occur.
* The **except** block catches any exceptions that occur in the try block.
* If an error occurs, it prints a message indicating that there was an error and suggests reviewing the code.

```
Output

Python ran into an error. Please take a look at your code again.

```