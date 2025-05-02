# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program that checks whether the given character is an uppercase alphabet, a lowercase alphabet, or not an alphabet (e.g., a digit or symbol).

## ALGORITHM :
1.	Start the program.

Import the Scanner class from the java.util package.

Define the main class Main.

Inside the main() method:

a. Create a Scanner object to read input.

b. Read a single character from the user.

c. Use Character.isUpperCase() to check if the character is uppercase.

d. If true, print "Upper Case".

e. Otherwise, use Character.isLowerCase() to check if the character is lowercase.

f. If true, print "Lower Case".

g. If both conditions are false, print "Digit".

End the program.


## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        char ch=sc.next().charAt(0);
        if(Character.isUpperCase(ch)){
            System.out.println("Upper Case");
        }
        else if(Character.isLowerCase(ch)){
            System.out.println("Lower Case");
        }
        else{
            System.out.println("Digit");
        }
    }
}
```


## OUTPUT:

Input	   Expected	      Got	 
a        Lower Case     Lower Case
8        Digit          Digit

## RESULT:
Thus, a Java program was successfully written to check whether the given character is an uppercase alphabet, a lowercase alphabet, or a digit, and it displays the result accordingly.
