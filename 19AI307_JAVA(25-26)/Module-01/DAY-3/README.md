# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to reverse a number using a while loop. For example, if the input is 1234, the output should be 4321

## AIM:
To write a Java program that reverses a given number using a `while` loop.

## ALGORITHM:
1. Start the program.
2. Read an integer `n` from the user.
3. Initialize `rev = 0` to store the reversed number.
4. Repeat the following steps while `n != 0`:
   - Find the last digit: `digit = n % 10`
   - Append the digit to the reversed number: `rev = rev * 10 + digit`
   - Remove the last digit: `n = n / 10`
5. After the loop ends, print the reversed number.
6. End the program.

## PROGRAM:
 ```
Program to implement a Looping Statement using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## SOURCE CODE:
```
import java.util.*;
public class Sample
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int rev = 0;
        while (n!=0)
        {
            int digit = n%10;
            rev = (rev*10) + digit;
            n/=10;
        }
        System.out.print("Reversed number: "+rev);
    }
}
```

## OUTPUT:
<img width="653" height="247" alt="image" src="https://github.com/user-attachments/assets/393a2ff7-5b6a-4295-a1ed-a890b31529f3" />

## RESULT:
The program successfully reverses the given number using a `while` loop and displays the reversed output.
