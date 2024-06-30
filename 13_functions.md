### 1. Defining and Calling a Function to Print "Hi"

```
def functionName():
    for i in range(0, 5):
    print("Hi")

functionName()
```

Explanation:
* Defining the Function:

    ```
    def functionName():
    ```
    * This line defines a function named functionName. Functions in Python are defined using the def keyword.

* For Loop Inside the Function:

    ```
    for i in range(0, 5):
    ```
    * This for loop iterates over a range of numbers from 0 to 4. The range(0, 5) function generates a sequence of numbers from 0 to 4.

* Printing "Hi":

    ```
    print("Hi")
    ```
    * Inside the loop, the print("Hi") statement is executed, which prints "Hi" to the console each time the loop runs.

* Calling the Function:

    ```
    functionName()
    ```
    * This line calls the functionName function, which executes the code inside the function.

```
Output:

Hi
Hi
Hi
Hi
Hi
```

### 2. Defining and Using a Function to Add Two Numbers

```
def addNum(firstNum, secondNum):
    return firstNum + secondNum

addNum(45, 3)
```

Explanation:

* Defining the Function:

    ```
    def addNum(firstNum, secondNum):
    ```
    * This line defines a function named addNum that takes two parameters: firstNum and secondNum.

* Returning the Sum:

    ```
    return firstNum + secondNum
    ```
    * The return statement calculates the sum of firstNum and secondNum and returns the result.

* Calling the Function:

    ```
    addNum(45, 3)
    ```
    * This line calls the addNum function with arguments 45 and 3. The function returns the sum of these two numbers, which is 48.

```
Output:

48
```