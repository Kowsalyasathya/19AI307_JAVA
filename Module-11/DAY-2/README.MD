# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To create a Java program to retrieve key-value pairs from a Hashtable, display the size of the Hashtable, and clear the Hashtable using the clear() method.

## ALGORITHM :

1.	Start

2.	Import `java.util.*`

3. Define a class with the main method

4.	Create a Scanner object to read user input.

5.	Read the number of entries (n) from the user.

6.	Create a Hashtable<Integer, String> to store keys and values.

7. Use a loop to:

-Read an integer key.

-Read a corresponding string value.

-Store the key-value pair in the hashtable using .put()

8. Use a loop to iterate through the hashtable using .keySet() and display each key and its corresponding value.

9. Print the size of the map using .size().

10. Clear the hashtable using .clear().

11. Print the size again to confirm it is empty.

12. End the program

## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: Kowsalya M 
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:
```python
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new Hashtable<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Size of Map: " + map.size()); map.clear(); 
System.out.println("Size of Map: " + map.size()); 

 }  
}  
```

## OUTPUT:
```
Input	  Expected	               Got	
2        key: 101 value: krishna     key: 101 value: krishna
100      key: 100 value: sri         key: 100 value: sri
sri      Size of Map: 2              Size of Map: 2
101      Size of Map: 0              Size of Map: 0
krishna

3        key: 107 value: collection  key: 107 value: collection
103      key: 104 value: java        key: 104 value: java
top      key: 103 value: top         key: 103 value: top
104      Size of Map: 3              Size of Map: 3
java     Size of Map: 0              Size of Map: 0
107
collection

2        key: 201 value: river       key: 201 value: river
201      key: 100 value: kite        key: 100 value: kite
river    Size of Map: 2              Size of Map: 2
100      Size of Map: 0              Size of Map: 0
kite
```

## RESULT:
Thus, the Java program was successfully created to retrieve key-value pairs from a Hashtable, display its size, and clear it using the clear() method.







