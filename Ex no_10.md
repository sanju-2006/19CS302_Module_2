# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE: 19/05/25
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: 
RegisterNumber:  
*/
```

#include <stdio.h>

// Function to calculate factorial
int factorial(int n) {
    int fact = 1;
    for(int i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int num, result;

    scanf("%d", &num);

    if(num < 0) {
        printf("Factorial is not defined for negative numbers.\n");
    } else {
        result = factorial(num);
        printf("Factorial of %d is %d\n", num, result);
    }

    return 0;
}

## Output:
Factorial of 5 is 120

## Result:
Thus the program was executed and the output was verified successfully.
