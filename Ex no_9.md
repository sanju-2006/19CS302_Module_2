# EX 9 C program to find the sum of odd digits using do while loop.
## DATE: 19/05/25
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: 
RegisterNumber:  
*/
```

#include <stdio.h>

int main() {
    int num, sum = 0, digit;
    scanf("%d", &num);

    do {
        digit = num % 10;
        if (digit % 2 != 0) {
            sum += digit;
        }
        num = num / 10;
    } while (num > 0);

    printf("Sum of odd digits = %d\n", sum);

    return 0;
}
## Output:
Sum of odd digits = 9

## Result:
Thus the program was executed and the output was verified successfully.
