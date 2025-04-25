# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To define a class named Date with day, month, and year as data members, get the joining date of an employee from the user, and display it in the format day:month:year using the main() method inside a class named Test.

## ALGORITHM :

1.Start the program.

2.Define a class named Date.

3.In the Date class, declare three integer variables: day, month, and year.

4.Define a class named Test.

5.In the main() method of the Test class:

6.Create a Scanner object to get input from the user.

7.Create an object of the Date class.

8.Read the values for day, month, and year from the user.

9.Store the values into the object.

10.Print the date in the format day:month:year.

11.End the program.

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

![image](https://github.com/user-attachments/assets/111d639e-b9f5-4061-a240-50e826aadd27)


## RESULT:
Thus, the class named Date with integer variables day, month, and year was created successfully.
