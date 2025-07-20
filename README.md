This repository contains two Python programs focused on recursion, mathematical calculations, and usage of built-in Python libraries like math.

📂 Task 1: Factorial of a Number using Recursion
File: Task-3_1.py

✅ Description:
This program calculates the factorial of a number entered by the user using a recursive function.

✅ Code Logic:
python
def fac(n):
    if n < 2:
        return 1
    else:
        return n * fac(n - 1)

n = int(input("Enter a number: "))
result = fac(n)
print(f"Factorial of {n} is: {result}")

📌 Example Output:
yaml
Enter a number: 5
Factorial of 5 is: 120
📂 Task 2: Mathematical Operations using Math Module
File: Task-3_2.py

✅ Description:
This program performs the following mathematical operations on a user-input number:

Square root

Logarithm (natural log)

Sine value

It uses Python’s built-in math module for calculations.

✅ Code Logic:
python
from math import *

a = int(input("Enter a number: "))
b = sqrt(a)
c = log(a)
d = sin(a)

print("Square root: ", b)
print("Logarithm: ", c)
print("Sine: ", d)

📌 Example Output:
yaml
Enter a number: 10
Square root: 3.1622776601683795
Logarithm: 2.302585092994046
Sine: -0.5440211108893698


🚀 How to Run
bash
python Task-3_1.py
python Task-3_2.py

💡 Author
Vikram Gupta
GitHub: vikram3008
