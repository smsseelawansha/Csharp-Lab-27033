
Question 03).

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


Question 04).

In this code, there are two classes: Program and HelloClass. The Program class contains the Main method, which serves as the entry point of the program.

Inside the Main method, an instance of the HelloClass is created and assigned to the variable helloObject. Then, the SayHello method of the helloObject is called.

Moving to the HelloClass, it has a private method named SayHello that doesn't take any parameters. This method simply displays the message "Hello, World!" to the console using the Console.WriteLine statement.

However, there is an issue in this code. Since the SayHello method in HelloClass is declared as private, it cannot be accessed from the Program class. Therefore, attempting to call the SayHello method using the helloObject in the Main method will result in a compilation error.

To fix this, we need to change the access modifier of the SayHello method in HelloClass to public. Once we make this change, the SayHello method will be accessible from the Program class, and the program will be able to execute successfully, printing "Hello, World!" to the console 

Question 05).

The program starts by declaring an integer array called "array" with a size of 10, which means it can store 10 integer values.

The user is prompted to enter 10 numbers one by one. The program uses a loop to iterate over the array's length and asks the user for input at each iteration. The entered numbers are stored in the corresponding positions of the array.

An object of the "ArrayOperations" class is created. This class contains methods to perform various operations on arrays.

The program calls the "FindMinimum" method of the "ArrayOperations" class, passing the "array" as a parameter. This method iterates over the array elements to find the smallest value and returns it.

Similarly, the program calls the "FindMaximum" method to find and return the largest value in the array.

The "FindAverage" method is invoked to calculate the average value of the numbers in the array. It adds up all the elements in the array and divides the sum by the array length. The average value is then returned.

The "ReverseArray" method is used to reverse the order of values in the array. It creates a new array and populates it with the elements of the original array in reverse order. The reversed array is then returned.

The program displays the minimum value, maximum value, average value, and the reversed array to the user using the "Console.WriteLine" method.

The program pauses and waits for the user to press the Enter key before terminating.

The "ArrayOperations" class contains methods specific to array operations. The "FindMinimum" method iterates over the array elements to find the smallest value and returns it. The "FindMaximum" method does the same to find the largest value. The "FindAverage" method calculates the average by summing all the array elements and dividing by the array length. The "ReverseArray" method creates a new array and fills it with the elements of the original array in reverse order.

In summary, this code allows the user to input 10 numbers into an array and performs operations to find the minimum, maximum, and average values, as well as reverse the order of the values in the array using the "ArrayOperations" class. The results are then displayed to the user.




