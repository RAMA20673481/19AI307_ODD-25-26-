# Ex.No:2(A) CLASS AND OBJECT
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
        Scanner scanner = new Scanner(System.in);

        
        Car car1 = new Car();
        car1.brand = scanner.nextLine();
        car1.color = scanner.nextLine();
        car1.year = scanner.nextInt();
        scanner.nextLine();

        
        Car car2 = new Car();
        car2.brand = scanner.nextLine();
        car2.color = scanner.nextLine();
        car2.year = scanner.nextInt();

        car1.printDetails();
        car2.printDetails();

        scanner.close();
    }
}
```


## OUTPUT:
<img width="597" height="685" alt="image" src="https://github.com/user-attachments/assets/05ebe553-f279-4f17-b125-675b4afd47bd" />


## RESULT:
Therefore,the program successfully creates two Car objects and assigns values to their attributes.



