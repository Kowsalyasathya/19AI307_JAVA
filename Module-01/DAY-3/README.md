# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069 
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        int num;
        Scanner input=new Scanner(System.in);
        num=input.nextInt();
        if(num==0)
          System.out.print("Given number is Zero");
        else
          System.out.print(num+" is Non-Zero");
    }
}
```



## OUTPUT:

![437393571-cc5d969e-151f-4d0e-ad62-999f1c1dbff1](https://github.com/user-attachments/assets/d9ae7bf3-6195-459c-8898-ba6c6da9bdb9)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

