# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE: 19/05/25
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output 

## Program:
```

#include <stdio.h>

void multiply();
void divide();

int main() {
    multiply();
    divide();
    return 0;
}

void multiply() {
    int a, b, result;
    printf("Enter two numbers for multiplication: ");
    scanf("%d %d", &a, &b);
    result = a * b;
    printf("Multiplication = %d\n", result);
}

void divide() {
    float a, b, result;
    printf("Enter two numbers for division: ");
    scanf("%f %f", &a, &b);
    if(b != 0)
        result = a / b;
    else {
        printf("Division by zero is not allowed.\n");
        return;
    }
    printf("Division = %.2f\n", result);
}

## Output:

Enter two numbers for multiplication: 6 4
Multiplication = 24
Enter two numbers for division: 8 2
Division = 4.00

## Result:
Thus the program was executed and the output was verified successfully.
