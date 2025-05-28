# Ex.No:12(D) JAVA QUEUE
## AIM:

To write a Java program to print the top element and remove it from the PriorityQueue container.

## ALGORITHM :
1.	Start the Program
2.	Import the necessary Java packages.
3.	Define the PriorityQueueDemo class with the main method.
4.	Initialize a PriorityQueue<Integer> object.
5.	Read the number of elements n from the user.
6.	Use a loop to read n integers and add them to the queue.
7.	Display and remove the top element using the poll() method.
8.	Display the remaining elements in the queue.
9.	End the program.

## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:
```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("Display the remove element of PriorityQueue:");
		System.out.println(pQueue.poll());
		System.out.println("Display the element of PriorityQueue:");
		System.out.println(pQueue);

		
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/af36097d-627f-4427-8c9a-e1e619d951c9)


## RESULT:
Thus, the Java program to print the top element and remove it from the PriorityQueue container was successfully executed.

