```
#include <stdio.h>
#include <stdlib.h>

void add() {
    float num1, num2;
    printf("Enter first number: ");
    scanf("%f", &num1);
    printf("Enter second number: ");
    scanf("%f", &num2);
    printf("%.2f + %.2f = %.2f\n", num1, num2, num1 + num2);
}

void subtract() {
    float num1, num2;
    printf("Enter first number: ");
    scanf("%f", &num1);
    printf("Enter second number: ");
    scanf("%f", &num2);
    printf("%.2f - %.2f = %.2f\n", num1, num2, num1 - num2);
}

void multiply() {
    float num1, num2;
    printf("Enter first number: ");
    scanf("%f", &num1);
    printf("Enter second number: ");
    scanf("%f", &num2);
    printf("%.2f * %.2f = %.2f\n", num1, num2, num1 * num2);
}

void divide() {
    float num1, num2;
    printf("Enter first number: ");
    scanf("%f", &num1);
    printf("Enter second number: ");
    scanf("%f", &num2);
    if (num2 != 0)
        printf("%.2f / %.2f = %.2f\n", num1, num2, num1 / num2);
    else
        printf("Error: Division by zero is not allowed\n");
}

int main() {
    int choice;
    while (1) {
        printf("Simple Calculator\n");
        printf("1. Addition\n");
        printf("2. Subtraction\n");
        printf("3. Multiplication\n");
        printf("4. Division\n");
        printf("5. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                add();
                break;
            case 2:
                subtract();
                break;
            case 3:
                multiply();
                break;
            case 4:
                divide();
                break;
            case 5:
                printf("Exiting...\n");
                exit(0);
            default:
                printf("Invalid choice. Please try again.\n");
        }
    }
    return 0;
}
```
