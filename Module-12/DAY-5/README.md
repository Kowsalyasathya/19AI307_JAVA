# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To write a Java program to display the removal element from the Deque using the getLast() method in Java Collection (using Strings).

## ALGORITHM :

1.	Start the program.
2.	Import the necessary Java packages.
3.	Create a Deque<String> using ArrayDeque.
4.	Read the number of string elements n from the user.
5.	Loop n times to add strings into the Deque using offer().
6.	Display the entire Deque.
7.	Use getLast() to get and display the last element.
8.	End the program.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Deque<String> dq=new ArrayDeque<String>();
        Scanner inp=new Scanner(System.in);
        int n=inp.nextInt();
        for(int i=0;i<n;i++)
        {
            dq.offer(inp.next());
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(dq);
        System.out.println(dq.getLast());
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/00a48264-021f-4b3e-9aa9-1f7f882c7dd8)


## RESULT:

Thus, the Java program successfully demonstrates how to use getLast() to display the last element from a Deque of strings.


