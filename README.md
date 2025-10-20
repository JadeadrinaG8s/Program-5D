# Program-5D
C module 5
EX NO-5)D) a program in C to check whether a character is Hexadecimal Digit or not.
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a program in C to check whether a character is Hexadecimal Digit or not.
ALGORITHM:
1)Take a character as input from the user.2)check if character is hexadecimal or not using isxdigit()function.3)printf the output using printf() function.
PROGRAM:
```
#include<stdio.h>
#include<ctype.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if(isxdigit(ch)==0)
    printf("The entered character is not a hexadecimal digit.");
    else
    printf("The entered character is a hexadecimal digit.");
}
```
OUTPUT:
<img width="1172" height="221" alt="Screenshot 2025-10-20 085105" src="https://github.com/user-attachments/assets/a5e98399-a752-471a-a5a1-e771ffc7efa9" />
RESULT:
Thus,a program in C to check whether a character is Hexadecimal Digit or not 
