# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Start and read a character ch (e.g., $).

2.Check if ch is between 'A' to 'Z' → it's uppercase (using ternary operator).

3.Else if ch is between 'a' to 'z' → it's lowercase; else if between '0' to '9' → it's a number.

4.If none of the above, it's a special character. Print the result.

## Program:
```
/*
C program to convert the given string to lowercase without using string functions.
Developed by: Devika N
RegisterNumber:  212222060038
#include <stdio.h>

int main() {
    char ch = '$';

    // Using conditional operator to determine character type
    (ch >= 'A' && ch <= 'Z') ? printf("Uppercase Letter\n") :
    (ch >= 'a' && ch <= 'z') ? printf("Lowercase Letter\n") :
    (ch >= '0' && ch <= '9') ? printf("Number\n") :
    printf("Special Character\n");

    return 0;
}

*/
```

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/942fa671-66ba-4174-94a1-dca927eabda9" />



## Result:
Thus the program was executed and the output was verified successfully.
