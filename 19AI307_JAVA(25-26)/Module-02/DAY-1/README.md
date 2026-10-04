# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Define a class Car with brand (String), color (String), and year (int). Create 2 different objects of Car  Assign values to attributes. Print the details of both cars.import java.util.Scanner;
## AIM:
To define a class Car with attributes brand, color, and year; create two objects of the class; assign values to their attributes; and print the details of both cars.

## ALGORITHM :
1. Define a class Car with three data members:

     String brand
     String color
     int year
 and a method printDetails() to display these values.

2. In the main() method, create a Scanner object to read user inputs.

3. Create the first object car1 and read its brand, color, and year from the user.

4. Create the second object car2 and read its brand, color, and year.

5. Call printDetails() for car1 to display its information.

6. Call printDetails() for car2 to display its information.

7.Close the scanner and end the program.


## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: HARISH KUMAR S
RegisterNumber: 212224230091
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class Car {
    String brand;
    String color;
    int year;

    void printDetails() {
        System.out.println("Brand: " + brand);
        System.out.println("Color: " + color);
        System.out.println("Year: " + year);
    }
}

class prog {
    public static void main(String[] args) {
