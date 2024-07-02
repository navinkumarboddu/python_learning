### eval() and exec() function

```
# Using eval() Function
eval('print("hello")')  # Output: hello

eval("23*5")           # Output: 115

# Using exec() Function
program = '''
print('Hi There')
print('My name is Bob')
'''

exec(program)
```

Explanation

* Using eval() Function:
  <br />
  \
    eval('print("hello")'):
        The eval() function parses the expression passed to it and executes Python expressions within the program.
        Here, eval('print("hello")') evaluates the print("hello") expression, which outputs hello.
  <br />
  \
    eval("23*5"):
        Similarly, eval("23*5") evaluates the arithmetic expression 23 * 5 and returns the result, which is 115.
  <br />
  \
  ```
    Example Outputs:
    hello
    115
  ```

* Using exec() Function:
  <br />
  
  - Defining a Multi-Line String with Program Code:
  <br />
  
  ```  
    program = '''
    print('Hi There')
    print('My name is Bob')
    '''
  ```
  <br />
  
  *** Here, a multi-line string containing two print statements is assigned to the variable program.
  <br />

  <br />
  
  - Executing the Program:

    exec(program)

    - The exec() function executes the dynamically created program stored in the program variable.
    - The code inside the program string is executed as if it were a regular Python program.

    ```
    Example Outputs:

python

Hi There
My name is Bob

