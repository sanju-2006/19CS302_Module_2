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
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: 
RegisterNumber:  
*/
```

/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: [Your Name]
RegisterNumber: [Your Register Number]
*/

#include <stdio.h>

void multiply();
void divide();

int main() {
    multiply();
    divide();
    return 0;
}

void multiply() {
    int a, b, product;
    scanf("%d %d", &a, &b);
    product = a * b;
    printf("Multiplication = %d\n", product);
}

void divide() {
    float a, b, result;
    scanf("%f %f", &a, &b);
    if(b != 0) {
        result = a / b;
        printf("Division = %.2f\n", result);
    } else {
        printf("Division by zero is not allowed.\n");
    }
}


## Output:

Multiplication = 42
Division = 7.00



## Result:
Thus the program was executed and the output was verified successfully.
