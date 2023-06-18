This code is a console application that enables users to perform arithmetic operations based on their input. The program follows these steps:

It presents a menu to the user, displaying the available choices of arithmetic operations: addition, subtraction, multiplication, and division.
The user selects their desired operation by entering a corresponding number (1 for addition, 2 for subtraction, 3 for multiplication, and 4 for division).
The program prompts the user to enter two numbers, num1 and num2, which will be used in the arithmetic operation.
An instance of the CalculateValues class, named calculator, is created to perform the arithmetic operations.
A variable named result is initialized to store the computed result.
Using a switch statement, the program identifies the user's choice and calls the corresponding method in the CalculateValues class, passing in num1 and num2 as parameters. The computed result is then assigned to the result variable.
If the user enters an invalid choice (a number other than 1, 2, 3, or 4), the program displays an "Invalid choice" message.
Finally, the program displays the computed result to the user by concatenating it with the "Your answer: " message.
The program waits for the user to press the Enter key before terminating.
The CalculateValues class contains four methods: Addition, Subtraction, Multiplication, and Division. Each method accepts two integer parameters and performs the corresponding arithmetic operation. The computed result is then returned.

Overall, this code allows users to select an arithmetic operation, input two numbers, and receive the result of the chosen operation.
