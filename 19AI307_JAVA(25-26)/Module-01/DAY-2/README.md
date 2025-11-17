# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
You are given the lengths of three sides of a triangle. Determine whether the triangle is:

- **Equilateral** – all sides equal  
- **Isosceles** – two sides equal  
- **Scalene** – all sides different  

If the sides don’t form a valid triangle (triangle inequality fails), print:

- **Not a triangle**

## AIM:
To read three side lengths of a triangle and determine whether the triangle is **Equilateral**, **Isosceles**, **Scalene**, or **Not a triangle** based on the triangle inequality rules.

## ALGORITHM:
1. Start the program.
2. Create an integer array of size 3.
3. Read three integers from the user and store them in the array.
4. Assign the values to variables `a`, `b`, and `c`.
5. Check the **triangle inequality condition**:
   - If `(a + b <= c)` OR `(a + c <= b)` OR `(b + c <= a)`:
     - Print **"Not a triangle"**.
6. If the above condition is false:
   - If all three sides are equal (`a == b` and `a == c`):
     - Print **"Equilateral"**.
   - Else if any two sides are equal (`a == b` or `a == c` or `b == c`):
     - Print **"Isosceles"**.
   - Else:
     - Print **"Scalene"**.
7. End the program.

## PROGRAM:
 ```
Program to implement a conditional statement using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## SOURCE CODE:
```
import java.util.*;
public class A
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        int arr[] = new int[3];
        for (int i=0; i<3; i++) arr[i] = s.nextInt();
        
        int a = arr[0], b = arr[1], c = arr[2];
        
        if (a+b<=c || a+c<=b || b+c<=a) System.out.print("Not a triangle");
        else if (a==b && a==c) System.out.print("Equilateral");
        else if (a == b || a == c || b == c) System.out.print("Isosceles");
        else
        {
            System.out.print("Scalene");
        }
    }
}
```

## OUTPUT:
<img width="629" height="152" alt="image" src="https://github.com/user-attachments/assets/333244dc-bb34-45a1-a5c5-5c3d7cbe911a" />


## RESULT:
The program successfully reads three side lengths, applies triangle inequality rules, and correctly identifies the triangle as **Equilateral**, **Isosceles**, **Scalene**, or **Not a triangle**.
