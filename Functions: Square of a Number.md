## Functions: Square of a Number using Function in C
## Aim
To write a C program that finds the square of a number using a function without arguments and without a return type.

## Algorithm
Define a function square without parameters.

Inside the square function, declare variables n and b.

Read an integer n from the user and calculate the square by multiplying n with itself.

Print the square value using printf with two decimal places.

In the main function, call the square function.

Return 0 to indicate successful execution.

## Program
```
#include <stdio.h>

void square() {
    int n;
    float b;

    printf("Enter an integer: ");
    scanf("%d", &n);

    b = n * n;
    printf("Square of %d is: %.2f\n", n, b);
}

int main() {
    square();
    return 0;
}
```


## Output
Sample Output 1:
Enter an integer: 5
Square of 5 is: 25.00

Sample Output 2:
Enter an integer: -3
Square of -3 is: 9.00

## Result
Program was implemented and executed.
