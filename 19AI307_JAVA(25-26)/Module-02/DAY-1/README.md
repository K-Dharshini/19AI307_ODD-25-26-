# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Vehicle with attributes as number, type and owner.

## AIM:
To write a Java program that creates a `Vehicle` class with attributes `number`, `type`, and `owner`, then reads the details of two vehicle objects and displays them.

## ALGORITHM :
1. Define a class `Vehicle` with three string attributes:
   - `number`
   - `type`
   - `owner`
2. In the `main` method:
   - Create a `Scanner` object to read input.
   - Create the first `Vehicle` object `v1`.
     - Read and assign `number`, `type`, and `owner`.
   - Create the second `Vehicle` object `v2`.
     - Read and assign `number`, `type`, and `owner`.
3. Print the details of both vehicles in the format:  
   `number | type | owner`
4. Close the scanner.
5. End the program.

## PROGRAM:
 ```
Program to implement a Class and Objects using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## SOURCE CODE:
```
import java.util.Scanner;
class Vehicle
{
    String number;
    String type;
    String owner;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vehicle v1 = new Vehicle();
        v1.number = sc.next();
        v1.type = sc.next();
        v1.owner = sc.next();

        Vehicle v2 = new Vehicle();
        v2.number = sc.next();
        v2.type = sc.next();
        v2.owner = sc.next();

        System.out.println(v1.number + " | " + v1.type + " | " + v1.owner);
        System.out.println(v2.number + " | " + v2.type + " | " + v2.owner);

        sc.close();
    }
}
```

## OUTPUT:
<img width="807" height="235" alt="image" src="https://github.com/user-attachments/assets/2104c1f9-a761-46be-8ed8-e6b1c55aba5f" />

## RESULT:
The program successfully creates two `Vehicle` objects, reads their details from the user, and prints them in the specified format.
