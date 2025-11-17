# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:
To write a Java program that demonstrates the use of:
- an **instance method** to perform addition,
- a **static method** to display information,
and calculates the sum of two numbers entered by the user.

## ALGORITHM :
1. Define a class `Calculator` with:
   - An instance method `add(int a, int b)` that returns the sum of two numbers.
   - A static method `info()` that prints a message indicating the calculator is ready.
2. In the `prog` class:
   - Create a `Scanner` object to read input.
   - Read two integers `a` and `b` from the user.
   - Create an object `c` of the `Calculator` class.
   - Call the static method `Calculator.info()` to display a message.
   - Call the instance method `c.add(a, b)` to compute the sum.
   - Print the result.
3. End the program.

## PROGRAM:
 ```
Program to implement Access Modifiers using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## SOURCE CODE:
```
import java.util.Scanner;

class Calculator {
    // Your Methods here
    int add(int a, int b)
    {
        return a+b;
    }
    
    static void info()
    {
        System.out.println("Calculator is ready");
    }
}

class prog {
    public static void main(String[] args) {
        // Your Function Initiation here
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        int b = s.nextInt();
        Calculator c = new Calculator();
        Calculator.info();
        System.out.println("Sum: "+c.add(a,b));
    }
}
```

## OUTPUT:
<img width="704" height="301" alt="image" src="https://github.com/user-attachments/assets/bbadc83b-b867-4db5-b918-292bf1f17c98" />

## RESULT:
The program successfully demonstrates the use of instance and static methods by displaying a message through the static method and printing the sum of two numbers using the instance method.
