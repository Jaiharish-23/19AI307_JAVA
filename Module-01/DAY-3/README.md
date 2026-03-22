# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```JAVA
/*
Program to implement a class & objects using Java
Developed by: JAI HARISH R
RegisterNumber: 21222404012
*/
import java.util.*;
class prog{
   public static void main(String[] args)
   {
       int num;
       Scanner sc = new Scanner(System.in);
       num=sc.nextInt();
       if (num==0)
       System.out.println("Given number is Zero");
       else
       System.out.println(num+" is Non-Zero");
   }
}
```


## OUTPUT:

<img width="518" height="178" alt="image" src="https://github.com/user-attachments/assets/10143e1f-f57d-46b3-a232-f22f543949f9" />


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

