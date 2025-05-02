# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a Java program to read 3 values and display all 3 values from an array using a single-dimensional array and standard method.

## ALGORITHM :

Start the program.
Import the Scanner class from the java.util package.
Define a class named ArrayExample.
Inside the main method:
i)Create a Scanner object called scanner to take user input.

ii)Declare an integer array values of size 3.

iii)Use a for loop to iterate from i = 0 to i < 3:

iv)Take input from the user and store it in values[i].

5.Define a standard method displayArray(int[] array):

i)Use a for loop to iterate through the array.

ii)Print each element followed by a space.

6.Call the displayArray method from the main method.

7.Close the scanner to release resources.

## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:

```
import java.util.*;
public class OnedimensionalStandard
{
	public static void main(String args[])
	{ 
	Scanner sc= new Scanner(System.in); 
	int[] a=new int[3];  
	for(int i=0;i<3;i++)
	{
	    a[i]=sc.nextInt();
	}
	 
	 
	System.out.println("One dimensional array elements are");    
	for(int i=0;i<3;i++)
	{
	   System.out.println(a[i]);
	}
	 

	}
}
```
## OUTPUT:

![437745067-0c4c72c4-c216-4774-aaeb-0da526924e7f](https://github.com/user-attachments/assets/a144feae-803d-4d8e-bcf6-620f2703a9f1)


## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


