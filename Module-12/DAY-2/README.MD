# Ex.No:12(B)   COMPARABLE INTERFACE
## AIM :
To write a Java program to display the student with the highest GPA from two given student details using the Comparable interface in Java collections.


## ALGORITHM :
1.	Start the Program.
2.	Import the necessary Java packages.
3.	Define the Student class and implement the Comparable<Student> interface.
4. Inside the Student class:
-	a) Declare attributes: name, gpa, and regNo.
-	b) Create a constructor to initialize these attributes.
- c) Override the compareTo() method to compare gpa values.\
- d) Provide getters and setters for all attributes.
5.	In the main method:
- a) Use Scanner to read input for two students.
- b) Compare the two student objects using compareTo().
- c) Display which student has the higher GPA or if both have the same GPA.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE INTERFACE using Java
Developed by: Kowsalya M
RegisterNumber: 212222230069
*/
```

## Sourcecode.java:
```
import java.util.*;
class Student implements Comparable<Student>
{
	private String name;
	private int gpa;
	private int regNo;
	
	//Constructor
	public Student(String name, int gpa, int regNo) {
		this.name = name;
		this.gpa = gpa;
		this.regNo = regNo;
	}
	
    //Override the comapareTo() method
	@Override
	public int compareTo(Student other)
	{
		return (int)(this.getGpa() - other.getGpa());//compare using GPA
	}
	
	//getters and setters
	public String getName() {
		return name;
	}
	public void setName(String name) {
		this.name = name;
	}
	
	public int getGpa() {
		return gpa;
	}
	public void setGpa(int gpa) {
		this.gpa = gpa;
	}
	
	public int getRegNo() {
		return regNo;
	}
	public void setRegNo(int regNo) {
		this.regNo = regNo;
	}
}

public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
		Student s1 = new Student(sc.next(), sc.nextInt(), sc.nextInt());
		Student s2 = new Student(sc.next(), sc.nextInt(), sc.nextInt());
		
		int comparisonResult = s1.compareTo(s2);
		
		if(comparisonResult > 0)
			System.out.println(s1.getName() + " has higher GPA");
		
		else if(comparisonResult < 0)
			System.out.println(s2.getName() + " has higher GPA");
		
		else
			System.out.println(s1.getName() + " and "+ s2.getName() + " have same GPA");
	}
}
```

## OUTPUT:
```
Input    	    Expected            	Got	
ram      hari has higher GPA     hari has higher GPA
6
3001
hari
7
3002

sasi     ganga has higher GPA    ganga has higher GPA
6
5001
ganga
8
6000

twin     praveen has higher GPA   praveen has higher GPA
5
100
praveen
8
101

```


## RESULT:
Thus, the Java program was successfully executed using the Comparable interface to compare two student objects and determine which one has the higher GPA.




