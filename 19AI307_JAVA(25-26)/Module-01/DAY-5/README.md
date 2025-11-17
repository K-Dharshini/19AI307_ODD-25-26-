# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to count the frequency of a given character in a string.

## AIM:
To write a Java program that reads a string and a character from the user, then counts and displays the frequency of that character in the string.

## ALGORITHM :
1. Start the program.
2. Create a `Scanner` object to read input.
3. Read a string `str` from the user.
4. Read a character `c` from the user.
5. Initialize a counter variable `count = 0`.
6. Loop through each character of the string:
   - If `str.charAt(i) == c`, increment `count`.
7. After the loop, print the total frequency of the character.
8. End the program.

## PROGRAM:
 ```
Program to implement a Strings and Math Function using Java
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
        String str = s.next();
        Character c = s.next().charAt(0);
        int count = 0;
        for (int i = 0; i < str.length(); i++)
        {
            if (str.charAt(i) == c) count++;
        }
        System.out.print("Frequency of '"+c+"' is: "+count);
    }
}
```

## OUTPUT:
<img width="669" height="302" alt="image" src="https://github.com/user-attachments/assets/1bc2c454-9526-46c3-b1d6-9200f55f182c" />

## RESULT:
The program successfully counts and displays the number of times a given character occurs in the input string.
