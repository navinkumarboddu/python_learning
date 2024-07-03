### Using input() Function
```
age = input("Enter your age:")  # User enters: 14
print(age)  # Output: '14'
```

Explanation :

* Using input() Function:
<br />
\
  - input("Enter your age:"):
    <br />
    \
    The input() function prompts the user for input and returns it as a string.
    Here, age = input("Enter your age:") prompts the user to enter their age and assigns the input (as a string) to the variable age.
    <br />
    \
    Example:
    ```
    User enters: 14
    age becomes '14'
    print(age) displays '14'.
    ```

### Comparing Input with Integer
```
if int(age) > 13:
print("Eligible for fb")  # Output: Eligible for fb
```
Explanation :

* Comparing Input with Integer:

  - if int(age) > 13::
    <br />
    \
        Since input() returns a string, you need to convert age to an integer to compare it with another integer.
        int(age) converts the string '14' to the integer 14.
        The condition int(age) > 13 evaluates to True, so the code inside the if block executes.
        Example Output:
        ```
        Eligible for fb
        ```

### Converting Strings to Numbers and Vice Versa
```
print(int("26"))         # Output: 26
print(float("123.456"))  # Output: 123.456
print(str(23))           # Output: '23'
```
Explanation :

* Converting Strings to Numbers and Vice Versa:
    <br />
    \
    - int("26"):
        The int() function converts a string to an integer.
        Here, int("26") converts the string "26" to the integer 26.
        
        Example Output:
        ```
        26
        ```

      - float("123.456"):

          The float() function converts a string to a float.
          Here, float("123.456") converts the string "123.456" to the float 123.456.
      Example Output:
      ```
        123.456
      ```

      - str(23):

          The str() function converts a number to a string.
          Here, str(23) converts the integer 23 to the string '23'.
      Example Output:
      ```
      '23'
      ```