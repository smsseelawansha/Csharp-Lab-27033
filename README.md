QUESTION 01

In the ConvertValues class, there are three methods that handle the conversion of kilometers to meters:

The KilometerToMeter() method prompts the user to input a distance in kilometers. It then reads the user's input, calculates the equivalent distance in meters by multiplying the kilometers by 1000, and displays the result in the console.

The KilometerToMeter(double kilometers) method accepts a parameter called kilometers, which represents the distance in kilometers. It calculates the equivalent distance in meters by multiplying the kilometers by 1000, and displays the result in the console.

The KilometerToMeterWithReturn(double kilometers) method is similar to the second method but has a return type of double. It accepts a parameter called kilometers, calculates the equivalent distance in meters by multiplying the kilometers by 1000, and returns the result as a double value.

In the Main method, an instance of the ConvertValues class is created, and the three methods are called to demonstrate their functionality:

The first method is called without any parameters, resulting in the user being prompted to enter a distance in kilometers. The input is then processed, and the corresponding distance in meters is displayed in the console.

The second method is called with a parameter value obtained from the user's input. The user is prompted to enter a distance in kilometers, and the input is passed as an argument to the method. The method calculates the distance in meters and displays the result in the console.

The third method is called similarly to the second method, but the calculated meter value is returned from the method. The returned value is stored in a variable called meters and then displayed in the console.


QUESTION 02

The code is a C# console application that calculates the area and circumference of a circle based on the user-provided radius. It consists of a class called "FindValues" and a "Program" class containing the main method.

In the "FindValues" class, there are two methods:

"FindArea(double radius)": This method calculates the area of the circle using the formula π * radius * radius. It takes the radius of the circle as a parameter and returns the calculated area as a double value.

"FindCircumference(double radius)": This method calculates the circumference of the circle using the formula 2 * π * radius. It also takes the radius as a parameter and returns the calculated circumference as a double value.

In the "Main" method of the "Program" class, an instance of the "FindValues" class is created using the "new" keyword. The program prompts the user to enter the radius of the circle and reads the input from the console, storing it in the "radius" variable.

Next, the program calls the "FindArea" method, passing the "radius" as an argument, to calculate the area of the circle. The calculated area is then stored in the "area" variable and displayed on the console.

Similarly, the program calls the "FindCircumference" method, passing the "radius" as an argument, to calculate the circumference of the circle. The calculated circumference is stored in the "circumference" variable and displayed on the console.

Finally, the program includes a "Console.ReadLine()" statement to prevent the console window from closing immediately, allowing the user to view the results before the program terminates.
