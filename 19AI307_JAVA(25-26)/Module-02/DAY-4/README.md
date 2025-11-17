# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Implement a class Employee with a parameterized constructor to initialize id, name, and salary.

## AIM:
To write a Java program that creates an `Employee` object using a parameterized constructor and retrieves the employee details using getter methods.

## ALGORITHM :
1. Define a class `A` with three data members:
   - `id`
   - `name`
   - `salary`
2. Create a parameterized constructor that initializes the above fields using the `this` keyword.
3. Provide getter methods:
   - `get_id()` to return the employee ID
   - `get_name()` to return the employee name
   - `get_salary()` to return the employee salary
4. In the `main` method:
   - Create a `Scanner` object.
   - Read `id`, `name`, and `salary` from the user.
   - Create an object of class `A` using the parameterized constructor.
   - Print the employee details using the getter methods.
5. End the program.

## PROGRAM:
 ```
Program to implement Variable scope and Constructor using Java
Developed by: DHARSHINI K
RegisterNumber: 212223230047
```

## SOURCE CODE:
```
import java.util.*;
class A
{
    int id;
    String name;
    float salary;
    A(int id, String name, float salary)
    {
        this.id = id;
        this.name = name;
        this.salary = salary;
    }
    
    public int get_id()
    {
        return id;
    }
    
    public String get_name()
    {
        return name;
    }
    
    public float get_salary()
    {
        return salary;
    }
}

public class Main
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        A a = new A(s.nextInt(), s.next(), s.nextFloat());
        System.out.println("Employee Details:");
        System.out.println("Employee ID: "+a.get_id());
        System.out.println("Employee Name: "+a.get_name());
        System.out.println("Employee Salary: "+a.get_salary());
    }
}
```

## OUTPUT:
<img width="758" height="448" alt="image" src="https://github.com/user-attachments/assets/a127a03d-f274-4479-bb52-fff095fbd634" />

## RESULT:
The program successfully creates an employee object using user input and displays the employee's ID, name, and salary using getter methods.
