# EX 7 C Program to Print a right triangle star Pattern
## DATE: 19/05/25
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: 
RegisterNumber:  
*/
```

#include <stdio.h>

int main() {
    int i, j, rows;
    scanf("%d", &rows);

    for(i = 1; i <= rows; i++) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}

## Output:

*
**
***
****
*****


## Result:
Thus the program was executed and the output was verified successfully.
