# Ex.No:5(A) INPUT STREAM READER 

## QUESTION:
Write a Java program to create a new file and write user-provided content into it.

## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a InputStreamReader using Java
Developed by: 
RegisterNumber:  
*/
```

## SOURCE CODE:
```
import java.io.File;
import java.io.FileWriter;
import java.io.IOException;
import java.util.Scanner;

public class CreateAndWriteFile {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        String fileName = scanner.nextLine();

        try {
            File file = new File(fileName);
            
            if (file.createNewFile()) {
                System.out.println("File created: " + file.getName());

                String content = scanner.nextLine();

                FileWriter writer = new FileWriter(file);
                writer.write(content);
                writer.close();

                System.out.println("Content written to the file successfully.");
            } else {
                System.out.println("File already exists.");
            }

        } catch (IOException e) {
            System.out.println("An error occurred: " + e.getMessage());
        }

        scanner.close();
    }
}
```

## OUTPUT:



## RESULT:

