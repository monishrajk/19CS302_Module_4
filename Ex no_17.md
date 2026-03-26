# EX 17 C Program to compare two strings without using strcmp().
## DATE:
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
Read the input string from the user.
Copy each character from the input string to another string using a for loop until the null character is reached.
Count the total number of characters in the string (excluding newline if present).
Null-terminate the copied string.
Print the copied string and the total character count.
## Program:
```
/*
 C Program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using for loop.
Developed by: Devika N
RegisterNumber: 212222060038
#include <stdio.h>
#include <string.h>
 
int main()
{
  	char S1[100], S2[100];
  	int i,j,c=0;
 
   scanf("%[^\n]",S1);
   scanf("%[^\n]",S2);
   for(i=0;S1[i]!='\0';i++)
   {
       S2[i]=S1[i];
   }
   S2[i]='\0';
   printf("s2:%s",S2);
   for(j=0;S2[j]!='\0';j++)
   {
       c++;
   }
   printf("\nTotal words=%d",c);
}
*/
```

## Output:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/25533b88-2d38-4a89-8301-109d6e2878a2" />


## Result:
Thus the program was executed and the output was verified successfully.
