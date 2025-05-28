# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to iterate through all elements in a tree set.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069  
*/
```

## Sourcecode.java:

```
 import java.util.*;
 public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        TreeSet<Integer> treeadd=new TreeSet<Integer>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            treeadd.add(sc.nextInt());
        }
        for(Integer element:treeadd){
            System.out.println(element);
        }
}
}
```

## OUTPUT:

![Screenshot 2025-05-23 161149](https://github.com/user-attachments/assets/7987e411-4941-4524-936a-42b20598d372)


## RESULT:
Thus the java program to iterate through all elements in a tree set was executed successfully.

