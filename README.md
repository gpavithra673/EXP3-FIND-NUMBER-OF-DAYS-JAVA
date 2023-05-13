# EXP3- FIND NUMBER OF DAYS USING JAVA
## AIM:
### To find the number of days in the given month using java
## PROCEDURE:
### 1.Create the class and declare the main method so that the JVM will identify the main program to run.
### 2.Declare a String to accept the string for month.
### 3.To get input from the user use 'Scanner' and import the package from 'java.util.Scanner'.
### 4.After getting the input use if cles condition or switich statement to find the days of respective month.
### 5.If the condition is satisfied the output will be displayed or else the input is taken to 'else' or 'default' part of the program.
### 6.Output will be displayed after the compilation of the code.
## CODE: 
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner num= new Scanner(System.in);
        Integer a=num.nextInt();
        switch (a){
            case 1:{
                System.out.print("January");
                break;
            }
            case 2:{
                System.out.print("february");
                break;
            }
            case 3:{
                System.out.print("March");
                break;
            }
            case 4:{
                System.out.print("April");
                break;
            }
            case 5:{
                System.out.print("May");
                break;
            }
            case 6:{
                System.out.print("june");
                break;
            }
            case 7:{
                System.out.print("july");
                break;
            }
            case 8:{
                System.out.print("August");
                break;
            }
            case 9:{
                System.out.print("September");
                break;
            }
            case 10:{
                System.out.print("October");
                break;
            }
            case 11:{
                System.out.print("november");
                break;
            }
            case 12:{
                System.out.print("December");
                break;
            }
            default:{
                System.out.print("Enter number between the given range(1-12)");
                break;
            }
        }
    }
}
```
## OUTPUT: 
![image](https://user-images.githubusercontent.com/93427264/224378132-5b998210-0eab-4758-a200-510f94a89b4c.png)
## RESULT:
Hence the output is obtained successfully using the above code for finding number of days in the given month.
