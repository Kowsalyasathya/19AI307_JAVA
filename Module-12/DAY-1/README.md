# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to sort keys in a TreeMap using a custom comparator.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define the class E with the main method:
-	a) Initialize a TreeMap<String, String> using a custom comparator.
-	b) Read an integer value size representing the number of key-value pairs.
4.	Loop through input:
-	a) Read two strings: a key (n1) and a value (s1).
-	b) Insert the key-value pair into the TreeMap.
5.	Display the contents of the TreeMap.
6.	Define a sort_key class that implements Comparator<String>:
-	Override the compare method to sort keys using compareTo().
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:

```
import java.util.*;
import java.util.Map.Entry;  
public class E {  
    public static void main(String args[]){  

   TreeMap<String,String> tree_map1 = new TreeMap<String,String>();      
  Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      String n1 = sc.next();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    
  System.out.println("Orginal TreeMap content: "+tree_map1);
    }
}
 class sort_key implements Comparator<String>{
     @Override
    public int compare(String str1, String str2) {
        return str1.compareTo(str2);
    }
     
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/d5d5f722-1287-426d-bdc9-223ef4a6b308)



## RESULT:
Thus, the Java program was successfully implemented to associate the specified value with the specified key in a TreeMap and sort the keys using a comparator.
