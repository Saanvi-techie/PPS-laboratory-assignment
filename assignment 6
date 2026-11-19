#include <stdio.h>

int factorial(int n);   // Declaration

int main() {
    int n = 5;
    printf("Factorial = %d", factorial(n));   // Call
    return 0;
}

int factorial(int n) {   // Definition
    if (n == 0) {
        return 1;
    }
    return n * factorial(n - 1);   // Recursive call
}
