#include <stdio.h>
int main() {
    int x,y;
    printf("Enter first number: ");
    scanf("%d", &x);
    printf("Enter second number: ");
    scanf("%d", &y);
    printf("Addition: %d\n", x+y);
    printf("Subtraction: %d\n", x - y);
    printf("Multiplication: %d\n", x * y);
    if (y != 0) {
        printf("Division: %.2f\n", (float)x / y);
    } else if {
        printf("Invalid Value.\n");
    }
    return 0;
}
