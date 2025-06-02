# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End







## PROGRAM:
 ```
/*
Program using Java
Developed by: SARAVANA KUMAR M
RegisterNumber:  212222230133
*/
```

## Sourcecode.java:
```
import java.util.*;
public class StringBufferExample{  
public static void main(String args[]){  
Scanner sc=new Scanner(System.in);
String str1=sc.nextLine();
String str2=sc.nextLine();
StringBuffer sb=new StringBuffer(str1+" ");  
sb.append(str2);  
System.out.println(sb);  
}  
}  
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/e2c9476f-b5d1-4338-a855-6f49d4ae2449)

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
