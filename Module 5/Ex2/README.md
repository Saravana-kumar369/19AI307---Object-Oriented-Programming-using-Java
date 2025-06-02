# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To create a Java program using a tightly encapsulated class that prints each character of the input string with space using setter and getter methods.

## ALGORITHM:
Step 1. Start the program and import Scanner for user input.

Step 2. Create a SetAndGet class with:

Step 3. A private String variable s.

Step 4. A method setlines to store user input.

Step 5. A method getlines that prints each character of the string separated by space.

Step 6. A Scanner object to read user input.

Step 7. A SetAndGet object to process the input.

Step 8. Read a string input from the user, set it using setlines, and print the spaced characters using getlines.

Step 9. Close the Scanner and end the program.

## PROGRAM:

/*
Program using Java
Developed by: SARAVANA KUMAR M
Register Number: 212222230133
*/
## SOURCE CODE:
```
import java.util.*;

public class SetAndGet {
    private String s;

    public void setlines(String s) {
        this.s = s;
    }

    public void getlines() {
        for (int i = 0; i < s.length(); i++) {
            System.out.print(s.charAt(i) + " ");
        }
    }

    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        SetAndGet obj = new SetAndGet();

        String str = sc.nextLine();
        obj.setlines(str);
        obj.getlines();

        sc.close();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/9b706ebc-d0ed-4cd8-9f67-0487e97cbb64)


## RESULT:
Thus, a Java program to print each character of a string with space using a tightly encapsulated class was executed successfully.
