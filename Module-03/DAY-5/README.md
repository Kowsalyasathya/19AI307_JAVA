# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that demonstrates a mutable string using StringBuilder and prints the modified string value.

## ALGORITHM :
Start the program.

Create a StringBuilder object with an initial string.

Modify the string using one of the StringBuilder methods (e.g., append, insert, replace, etc.).

Print the modified string.

End the program.
## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:

```
import java.util.*;
public class MutableStringEx { 
public static void main(String[ ] args) 
{ 
 Scanner sc=new Scanner(System.in);
 String str1=sc.nextLine();
 StringBuffer sb = new StringBuffer(str1); 
  sb.append(" Easy");
  sb.append(" today");
  System.out.println(sb); 
 } 
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/f934e66e-7edc-45c5-911a-b4c3f217f44e)


## RESULT:
Thus, the Java program successfully demonstrates the concept of a mutable string using StringBuilder and displays the modified string value.

