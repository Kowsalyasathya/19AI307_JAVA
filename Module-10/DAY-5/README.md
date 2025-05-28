# Ex.No:10(E)  JAVA LINKEDLIST get() METHOD

## AIM:
To write a Java program to create a LinkedList, read the size and elements from the user, and display the element from the LinkedList at a specific position using the get() method.
## ALGORITHM :

a.	Start the program.

b.	Import java.util.*.

c.	Create a Scanner object to read input from the user.

d.	Read the size of the LinkedList.

e.	Create a LinkedList<String> object.

f.Read n elements from the user and add them to the list.

g.Use the get() method to access and display the element at index 1.

h.End the program.



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKEDLIST get() METHOD
Developed by: Kowsalya M
RegisterNumber: 212222230069 
*/
```

## Sourcecode.java:
```python
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);
        int size=input.nextInt();
        LinkedList<String> l=new LinkedList<String>();
        for(int i=0;i<size;i++){
            l.add(input.next());
        }
        System.out.println("Element at index 1: "+ l.get(1));
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/96b8d776-abf9-40dd-8496-acca98ef62b5)


## RESULT:

Thus, the Java program was successfully implemented to create a LinkedList, store user-provided elements, and retrieve an element at a specific index using the get() method.
