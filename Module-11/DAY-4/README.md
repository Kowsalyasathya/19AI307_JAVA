# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To create a Java program to create and add mappings to a Hashtable and use the merge() method to insert a new entry using Map interface concepts.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a)  Create a Hashtable object using Map interface.
-	b)  Read integer n from user input (number of key-value pairs)
-	c)  Loop n times:
-	i)  Read a string key and integer value
-	ii) Insert into the map using put()
-	d)  Display the initial map.
-	e)  Use merge() to insert or update the entry "Shirt" with value 70 by summing old and new value.
-	f)  Display updated Shirt price and the updated map.
4.	End

## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Map<String,Integer> map=new Hashtable<>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            String b=sc.next();
            Integer a=sc.nextInt();
            map.put(b,a);
        }
        System.out.println("Map: "+map);
        int returnedValue=map.merge("Shirt",70,(oldValue,newValue)->oldValue+newValue);
        System.out.println("Price of Shirt: "+returnedValue);
        System.out.println("Updated Map: "+map);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/3a3bbe10-8398-4079-b47b-a383b2ed30f2)


## RESULT:
Thus, the Java program to create and add mappings to a Hashtable, and use the merge() method to insert and update entries using Map interface concepts was executed and verified successfully.




