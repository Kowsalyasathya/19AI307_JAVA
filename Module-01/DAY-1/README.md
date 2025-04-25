# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named Student with name and address variables, and then display these values using an object of the class.

## ALGORITHM :
1.Start the program.
2.Define a class name Student.
3.Inside the Student class, declare two String variables: name and address, and initialize them with "John" and "Chennai" respectively.
4.Define another class named Test.
5.In the Test class, define the main method.
6.Create an object obj of the Student class.
7.Access and print the values of name and address using the obj object.
8.End the program.

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Kowsalya M
RegisterNumber:  212222230069
*/
```

## Sourcecode.java:

```
public class Test{
    public static void main(String[] args)
    {
         Scanner scanner = new Scanner(System.in);
        Date in=new Date();
        int day,month,year;
        in.day = scanner.nextInt();

        in.month = scanner.nextInt();
 
        in.year = scanner.nextInt();
        String hour=String.format("%d",in.day);
        String min=String.format("%d",in.month);
        String secs=String.format("%d",in.year);
        
        System.out.println(hour+"/"+min+"/"+secs);
       
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/98cb3865-818c-4193-a266-ed8d48fee9f4)


## RESULT:
Thus, class named Student with name and address variables was created successfully.
