# Experiment1-java
## Aim:
To code a java program to print the arithmetic oprations.

## Algorithm:
Step 1:
Import the required packages.
Step 2:
Get the numbers from user using scanner package.
Step 3:
Do the arithmetic opration like addition , subtraction,multiplication,division,modulus.
Step 4:
Display the result.
## Code:
```
import java.util.Scanner;
public class Exp1 {
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        System.out.println("Sum= "+(a+b));
        System.out.println("Subtraction= "+(a-b));
        System.out.println("Multiplication= "+(a*b));
        System.out.println("Division= "+(a/b));
        System.out.println("Modulus= "+(a%b));

    }
}
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Experiment1-java/assets/93427594/12f05707-db1d-49bc-9878-04f0d708b044)


