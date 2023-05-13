# Experiment-2-JAVA
## AIM
To create a Java program to compare two numbers
## PROCEDURE
1. Import the Scanner class from the java.util package.
2. Define a public class named "Main".
3. Declare the main method with the signature "public static void main(String[] args)".
4. Inside the main method, create an instance of the Scanner class using "Scanner sc = new Scanner(System.in)" to read input from the user.
5. Declare integer variables "ab" and "cd" to store the user's input.
6. Use conditional statements to compare the values of "ab" and "cd"
7. End the main method and the Main class
## PROGRAM
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        if(a>b)
            System.out.println("A is greater");
        else if(a<b)
            System.out.println("B is greater");
        else
            System.out.println("A is equal to B");

    }
}
```
## OUTPUT
<img width="391" alt="image" src="https://github.com/Shavedha/Experiment-2-JAVA/assets/93427376/4ef04941-4cae-4df0-a805-5ad3893414ff">

## RESULT
Hence the two numbers were compared using Java programming language.
