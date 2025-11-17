# Ex.No:2(B) METHODS

## QUESTION:
Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).

## AIM:
To write a Java program that calculates the cube of a number using two separate methods:  
- one method to compute the square of a number  
- another method to compute the cube by using the square method.

## ALGORITHM :
1. Define a class `A` with two methods:
   - `square(int x)`: returns `x * x`
   - `cube(int x)`: returns `x * square(x)`
2. In the `main` method:
   - Create a `Scanner` object.
   - Read an integer `x` from the user.
   - Create an object of class `A`.
   - Call the `cube(x)` method and print the result.
3. End the program.

## PROGRAM:
 ```
Program to implement a Method using Java
Developed by: DHARSHINI K
Register Number: 212223230047  
```

## SOURCE CODE:
```
import java.util.*;

class A
{
    int cube(int x)
    {
       return x * square(x); 
    }
    
    int square(int x)
    {
        return x * x;
    }
}

public class Display
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        int x = s.nextInt();
        A a = new A();
        System.out.print(a.cube(x));
    }
}
```

## OUTPUT:
<img width="433" height="155" alt="image" src="https://github.com/user-attachments/assets/5951fbf7-c717-4a07-a01e-5bb616de6bfe" />

## RESULT:
The program successfully calculates the cube of the input number using method calling and displays the output.
