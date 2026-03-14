📘 Python Program: Addition of Two Numbers

📌 Overview

This Python program takes two numbers as input from the user and calculates their sum.
It demonstrates basic programming concepts such as user input, data type conversion, variables, and arithmetic operations.

⚙️ Source Code
num1 = float(input("Enter the number for addition : "))
num2 = float(input("Enter the number for addition : "))

num3 = num1 + num2

print(num3)
🧠 How the Program Works
1️⃣ Taking User Input
num1 = float(input("Enter the number for addition : "))

input() allows the user to enter a value.

float() converts the input into a floating-point number so that decimal values can also be used.

Example:

Enter the number for addition : 10.5
2️⃣ Taking the Second Number
num2 = float(input("Enter the number for addition : "))

The user enters the second number which is also converted to a float.

3️⃣ Performing Addition
num3 = num1 + num2

The program adds the two numbers and stores the result in the variable num3.

4️⃣ Displaying the Result
print(num3)

The final result (sum of the two numbers) is printed on the screen.

▶️ Example Execution
Input
Enter the number for addition : 15
Enter the number for addition : 20
Output
35.0
🔑 Key Concepts Used

User Input → input()

Type Conversion → float()

Variables

Arithmetic Operation → Addition (+)

Output → print()

⏱️ Time Complexity

O(1) – The program performs a fixed number of operations.

🚀 Possible Improvement

Better formatted output:

print("The sum is:", num3)

or

print(f"The sum of {num1} and {num2} is {num3}")
📚 Learning Outcome

After running this program, you will understand:

How to take input from users

How to convert strings to numbers

How to perform basic arithmetic operations in Python


