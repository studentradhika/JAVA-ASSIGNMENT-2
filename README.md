# JAVA-ASSIGNMENT-2
 Calculator Application 
 Overview

This Java-based Calculator Application allows users to perform basic arithmetic operations — addition, subtraction, multiplication, and division — through a menu-driven console interface.
It also demonstrates Object-Oriented Programming (OOP) concepts like method overloading, encapsulation, and exception handling.

 Features

 Addition (supports method overloading)

Add two integers

Add two doubles

Add three integers

✅ Subtraction
✅ Multiplication
✅ Division (with divide-by-zero exception handling)
✅ Menu-driven program for easy navigation

 Concepts Used
Concept	Description
Method Overloading	Multiple add() methods with different parameter lists
Encapsulation	Calculator class hides arithmetic logic
Exception Handling	try-catch-finally used in divide() to handle division by zero
Scanner Class	Used for user input
Loops & Switch Case	Used to build an interactive menu system
 Class Structure
1️ Calculator.java

Handles all arithmetic operations:

public int add(int a, int b)
public double add(double a, double b)
public int add(int a, int b, int c)
public int subtract(int a, int b)
public double multiply(double a, double b)
public double divide(int a, int b)


Includes exception handling in divide().

2️CalculatorApplication.java

Handles:

User interaction

Menu display

Input collection

Calls methods from Calculator class

🖥️ Sample Output
===============================
   CALCULATOR APPLICATION
1. Add Numbers
2. Subtract Numbers
3. Multiply Numbers
4. Divide Numbers
5. Exit
Enter your choice: 1

Choose type of addition:
1. Two Integers
2. Two Doubles
3. Three Integers
Enter choice: 3
Enter three integers separated by space: 2 3 4
Result: 9


Division Example (Handling Zero):

Enter dividend: 10
Enter divisor: 0
Cannot divide by zero!
Division operation completed.



3️ Compile and Run
javac CalculatorApplication.java
java CalculatorApplication

🧰 Example Menu Flow

   CALCULATOR APPLICATION
1. Add Numbers
2. Subtract Numbers
3. Multiply Numbers
4. Divide Numbers
5. Exit
Enter your choice: 2
Enter first integer: 9
Enter second integer: 5
Result: 4