# Java_Al-Altruists_089
Here’s the README file for your Java project:

Java Polymorphism and Exception Handling Project
Introduction
This project demonstrates two core Java programming concepts: polymorphism through interfaces and classes, and exception handling using try-catch-finally blocks.

Project Type
Java Application

Project Structure
The project is divided into two tasks:

Polymorphism with Payment Interface
Exception Handling with Division by Zero Scenario
Question 1: Payment Interface
Objective
The objective of this task is to create an interface named Payment with a method processPayment(). Two classes, CreditCardPayment and PayPalPayment, implement this interface and provide their unique implementations of the processPayment() method. This showcases polymorphism by allowing different classes to be referenced by a common Payment type.

Project Details
Interface Definition: Payment interface with a processPayment() method.
Implementing Classes:
CreditCardPayment: Simulates a credit card payment.
PayPalPayment: Simulates a PayPal payment.
Polymorphism Demonstration: Instances of CreditCardPayment and PayPalPayment are created, stored in Payment references, and their processPayment() methods are invoked.
Expected Output
The program prints unique messages for each payment type:

Copy code
Processing credit card payment...
Payment processed successfully.

Processing PayPal payment...
Payment processed successfully.
Question 2: Exception Handling with try-catch-finally
Objective
This task demonstrates the use of try, catch, and finally blocks to handle an ArithmeticException caused by division by zero. It ensures that a specific message is displayed when an exception occurs, and the finally block executes regardless of exception presence.

Project Details
Division by Zero Scenario: Prompts the user to enter two numbers and attempts division.
Exception Handling: If the divisor is zero, an ArithmeticException is caught and an error message is shown.
Finally Block: Prints a message to show that the finally block executes regardless of an exception.
Expected Output
When a division by zero is attempted:

vbnet
Copy code
Enter a number: 10
Enter another number: 0
Error: Division by zero is not allowed.
This code will always execute.
Submission Guidelines
Code Structure: Submit the project either as a single Java file or as separate files for each class.
Commenting: Ensure code readability with well-placed comments.
Testing: Test the code with various inputs to confirm functionality.
Screenshots: Attach screenshots demonstrating successful execution with sample inputs.
Technology Stack
Java: Used for implementing both tasks.
Exception Handling: Demonstrates safe handling of runtime errors.
