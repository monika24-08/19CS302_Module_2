# EX 7 C Program to Print a right triangle star Pattern
## DATE:23/22/2025
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1.Start the program.

2.Declare an integer variable for the number of rows.

3.Read the number of rows from the user.

4.Use nested loops to print stars (*) in a right triangle pattern.

5.End the program.
## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: MONIKA M
RegisterNumber: 212223060169
*/

#include <stdio.h>

int main()
{
    int rows, i, j;

    printf("Enter number of rows: ");
    scanf("%d", &rows);

    for(i = 1; i <= rows; i++)
    {
        for(j = 1; j <= i; j++)
        {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}

```

## Output:
<img width="366" height="403" alt="image" src="https://github.com/user-attachments/assets/c64957c6-c76d-4802-ae42-4286ae623162" />

## Result:
Thus the program was executed and the output was verified successfully.

## Result:
Thus the program was executed and the output was verified successfully.
