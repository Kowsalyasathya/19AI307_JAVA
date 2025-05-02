# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    static String dept="AIDS";
    static int age=18; 
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);
        String name1,name2;
        name1=input.nextLine();
        name2=input.nextLine();
        System.out.println("Student name: "+name1+" Department: "+dept+" Age: "+age);
        System.out.print("Student name: "+name2+" Department: "+dept+" Age: "+age);
    }
}
```



## OUTPUT:

![437395942-f5b58b3c-f6c1-420b-bc83-406970b30a71](https://github.com/user-attachments/assets/ea936bff-060a-4b2a-9ad7-fb114d970cbd)


## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

