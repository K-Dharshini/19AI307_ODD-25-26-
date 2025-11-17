# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely found a magic machine that tells her how two numbers relate to each other.
The machine supports all 6 relational operators:

| Operator | Meaning                     |
|---------|------------------------------|
| ==      | Is equal to                  |
| !=      | Is not equal to              |
| >       | Greater than                 |
| <       | Less than                    |
| >=      | Greater than or equal to     |
| <=      | Less than or equal to        |

Lovely enters two numbers. The machine prints the result (true or false) for each operator.

## Input Format
First line: First integer number (a)

Second line: Second integer number (b)

## Output Format
Print:

a == b: <true/false>  
a != b: <true/false>  
a > b: <true/false>  
a < b: <true/false>  
a >= b: <true/false>  
a <= b: <true/false>


## AIM:
To read two integer values from the user and display the results of all six relational operations (`==`, `!=`, `>`, `<`, `>=`, `<=`) between them.

## ALGORITHM :
1. Start the program.
2. Import the `Scanner` class to read user input.
3. Create a `Scanner` object.
4. Read the first integer `a`.
5. Read the second integer `b`.
6. Evaluate and print the result of:
   - `a == b`
   - `a != b`
   - `a > b`
   - `a < b`
   - `a >= b`
   - `a <= b`
7. End the program.

## PROGRAM:
 ```
Program to implement variables and Operators using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## Source code.java:
```
import java.util.*;
public class Sample
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println("a == b: "+(a==b));
        System.out.println("a != b: "+(a!=b));
        System.out.println("a > b: "+(a>b));
        System.out.println("a < b: "+(a<b));
        System.out.println("a >= b: "+(a>=b));
        System.out.println("a <= b: "+(a<=b));
    }
}
```

## OUTPUT:
<img width="560" height="271" alt="image" src="https://github.com/user-attachments/assets/0fd96b0e-e9f9-4b85-8634-27ab39096e13" />

## RESULT:
The program successfully reads two integers and displays the results of all relational operators (`==`, `!=`, `>`, `<`, `>=`, `<=`) correctly based on the given inputs.

