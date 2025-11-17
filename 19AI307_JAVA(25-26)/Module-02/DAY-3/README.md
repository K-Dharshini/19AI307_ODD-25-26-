# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
Write a Java program to create a class called Person with private instance variables name, age. and country. Provide public getter and setter methods to access and modify these variables.

## AIM:
To write a Java program that creates a `Person` class with private attributes (`name`, `age`, `country`) and uses getter and setter methods to assign and retrieve values entered by the user.

## ALGORITHM:
1. Define a class `Person` with three private data members:
   - `name`
   - `age`
   - `country`
2. Provide getter and setter methods for each data member:
   - `setName()`, `getName()`
   - `setAge()`, `getAge()`
   - `setCountry()`, `getCountry()`
3. In the `main` method:
   - Create a `Scanner` object to read input.
   - Create a `Person` object `p`.
   - Display `"Person 1"`.
   - Read the name, call `setName()`, then print it using `getName()`.
   - Read the age, call `setAge()`, then print it using `getAge()`.
   - Read the country, call `setCountry()`, then print it using `getCountry()`.
4. End the program.

## PROGRAM:
 ```
Program to implement Access Specifiers using Java
Developed by: DHARSHINI K
Register Number: 212223230047
```

## SOURCE CODE:
```
import java.util.*;
class Person {
     private String name;
     private int age;
     private String country;
     
     public String getName() {
          return name;
     }
     
     public void setName(String name) {
         this.name = name;
     }
     
     public int getAge() {
         return age;
     }
     
     public void setAge(int age) {
         this.age = age;
     }
     
     public void setCountry(String country) {
         this.country = country;
     }
     
     public String getCountry() {
         return country;
     }
}

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        Person p = new Person();
        System.out.println("Person 1");
        p.setName(sc.next());
        System.out.println("Name: "+p.getName());
        p.setAge(sc.nextInt());
        System.out.println("Age: "+p.getAge());
        p.setCountry(sc.next());
        System.out.println("Country: "+p.getCountry());
    }
}
```

## OUTPUT:
<img width="766" height="452" alt="image" src="https://github.com/user-attachments/assets/2913b892-9931-4224-996c-29b473347672" />

## RESULT:
The program successfully accepts the name, age, and country of a person, stores them using setter methods, and displays the values using getter methods.
