# Java-program-to-print-even-numbers-from-1-to-20

## AIM:
To write a java program that prints all the even numbers from 1 to 20.

##  PROCEDURE:

1. Create a Java class called "Even" and declare the main method inside it.
2. Print the message "The even numbers from 1 to 20 are listed below:" using System.out.print() method.
3. Declare an integer variable named "i".
4. Create a for loop that initializes the "i" variable to 1, checks if "i" is less than or equal to 20, and increments "i" by 1 on each iteration.
5. Within the for loop, use an if statement to check if the current value of "i" is even by checking if "i" is divisible by 2 with no remainder (i%2==0).
6. If the current value of "i" is even, print the value of i.
7. End the for loop and the main method.

## PROGRAM:
```
public class Even{
    public static void main(String[] args){
        System.out.print("The even numbers from 1 to 20 are listed below:");
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2==0)
            {
                System.out.print("\n"+i);
            }
        }
    }
}
```

## OUTPUT:
```
C:\Users\Dell\.jdks\openjdk-19.0.2\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\lib\idea_rt.jar=8209:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath "C:\Users\Dell\IdeaProjects\Java 1\out\production\Java 1" Even
The even numbers from 1 to 20 are listed below:
2
4
6
8
10
12
14
16
18
20
Process finished with exit code 0
```
## RESULT:
Thus the program to print all the even numbers from 1 to 20 is written and the output is verfied.
