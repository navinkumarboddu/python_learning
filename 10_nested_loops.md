### 1. nested Loop Example

```
for i in range(2, 30):
    # This loop iterates over numbers from 2 to 29.
    j = 2
    # Initializes the variable 'j' to 2 for checking divisors starting from 2.
    counter = 0
    # Initializes the variable 'counter' to 0 to track whether a number is prime or not.
    while j < i:
        # This loop checks each number 'j' from 2 up to (but not including) 'i'.
        if i % j == 0:
            # Checks if 'i' is divisible by 'j'.
            counter = 1
            # If 'i' is divisible by 'j', set 'counter' to 1 indicating 'i' is not a prime number.
            j = j + 1
            # Increment 'j' to check the next potential divisor.
        else:
            j = j + 1
            # If 'i' is not divisible by 'j', just increment 'j' to check the next potential divisor.
    if counter == 0:
        # After the while loop, if 'counter' is still 0, it means 'i' is a prime number.
        print(str(i) + " is a prime number")
        # Print that 'i' is a prime number.
    else:
        counter = 0
        # If 'counter' is 1, it means 'i' is not a prime number.
        # Reset 'counter' to 0 for the next iteration.
        
```

Output::

```
2 is a prime number
3 is a prime number
5 is a prime number
7 is a prime number
11 is a prime number
13 is a prime number
17 is a prime number
19 is a prime number
23 is a prime number
29 is a prime numbe
```