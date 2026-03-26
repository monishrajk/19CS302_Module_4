# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1. Read the input string from the user.
2. Read the character whose frequency is to be found.
3. Initialize a count variable to 0.
4. Loop through each character of the string:
     - If the current character matches the target character, increment count.
5. Print the count as the frequency of the character.


## Program:
```
#include<stdio.h>
int main()
{
   char ch, str[200];
   int i, frequency=0;

   scanf("%[^\n]%*c",str); 
  
  
   scanf("%c",&ch);

   for(i=0;str[i]!='\0';i++)
   {
       if(str[i]=='m'||str[i]=='p')
       {
           frequency++;
       }
   
       //add your code here
        
   }
printf("%d",frequency);
  
   return 0;
  }
```

## Output:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9b262e7e-2591-4183-a185-83fbf47dd885" />


## Result:
Thus the program was executed and the output was verified successfully.
