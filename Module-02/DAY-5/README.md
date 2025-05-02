# Ex.No:2(E)  Access Modifiers

## AIM:

To write a Java program using any one access modifier and display the odd numbers from 1 to 10 using a loop.

## ALGORITHM :

1.Start the program.

2.Define a class with a method using an access modifier (public, private, or protected).

3.Use a loop (for or while) to iterate numbers from 1 to 10.

4.For each number, check if it is odd (i.e., number % 2 != 0).

5.If odd, print the number.

6.End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:

```
public class Main {
    private void displayOddNumbers() {
        for (int i = 1; i <= 10; i += 2) {
            System.out.println(i);
        }
    }

    public static void main(String[] args) {
        Main main = new Main();
        main.displayOddNumbers();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/aebbea35-a240-4876-bd45-5973872d7aaf)


## RESULT:
Thus, the Java program successfully uses an access modifier and displays all odd numbers from 1 to 10 using a loop.



