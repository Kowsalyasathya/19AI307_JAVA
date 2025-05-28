# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To demonstrate how to create and add objects to a HashMap, and check whether the HashMap is empty or not.

## ALGORITHM :

a.	Import java.util.*.

b.	Create a HashMap using the HashMap interface.

c.	Read the number of entries (size) from the user.

d.	Loop size times to read key-value pairs and insert them into the map.

e. Use a for-each loop to iterate through the map and print all entries.

f. Use isEmpty() method to check whether the map is empty or not and display the result.

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
  boolean isEmpty = map.isEmpty(); System.out.println("Is HashMap is empty: " + isEmpty);
 }  
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/54c55769-8294-4564-a4d3-b750d10dbe95)


## RESULT:
Thus, the Java program successfully creates and adds entries into the HashMap and checks whether the map is empty or not.



