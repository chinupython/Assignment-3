This repository contains simple Python programs demonstrating recursion, loops, and math module usage.

#Task 1: Factorial Function

Problem Statement:
Write a Python program that:

Defines a function named factorial that takes a number as an argument and calculates its factorial (using recursion or loop).

Returns the calculated factorial.

Calls the function with a sample number and prints the output.

Code Example:

num = int(input("Enter a number : "))


def factorial(n):
    if n<2 :
        return 1
    else:
        return n*factorial(n-1)
result=factorial(num)
print("Factorial of " ,num ," is: ",result)


Expected Output:

Enter a number : 5
Factorial of  5  is:  120

#Task 2: Using the Math Module

Problem Statement:
Write a Python program that:

Asks the user for a number as input.

Uses the math module to calculate:

Square root of the number

Natural logarithm (base e) of the number

Sine of the number (in radians)

Displays the calculated results.

Code Example:

num = int(input("Enter a number: "))

from math import *
print("square root " ,sqrt(num))
print("logarithm " ,log(num))
print("sinh " ,sin(num))


Expected Output :

Enter a number: 25
square root  5.0
logarithm  3.2188758248682006
sinh  -0.13235175009777303


Square root of 25.0 : 5.0
Natural logarithm of 25.0 : 3.2188758248682006
Sine of 25.0 : -0.13235175009777303
