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

Using eval() Function:

    eval('print("hello")'):
        The eval() function parses the expression passed to it and executes Python expressions within the program.
        Here, eval('print("hello")') evaluates the print("hello") expression, which outputs hello.

    eval("23*5"):
        Similarly, eval("23*5") evaluates the arithmetic expression 23 * 5 and returns the result, which is 115.

    Example Outputs:

    python

    hello
    115


