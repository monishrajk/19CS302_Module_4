# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1.Start and initialize a = -300, b = -400, c = 500.

2.Compare a and b using conditional operator: temp = (a < b) ? a : b.

3.Compare temp and c using conditional operator: min = (temp < c) ? temp : c.

4.Print min as the minimum number.
## Program:
```
int main() {
    int a = -300, b = -400, c = 500;
    int min;

    // Using nested conditional operator to find the minimum
    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("Minimum between %d, %d and %d = %d\n", a, b, c, min);

    return 0;
}

```

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6fff2fe9-5b35-44ae-a089-3aa51de692e6" />



## Result:
Thus the program was executed and the output was verified successfully.
