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
    float square_value;
    printf("Enter a number: ");
    scanf("%d", &n);
    square_value = (float)n * n;
    printf("The square of %d is: %.2f\n", n, square_value);
}

int main() {
    square();
    return 0;  
}
```

## Output
Sample Output 1:
Enter a number: 5
The square of 5 is: 25.00

Sample Output 2:
Enter a number: 8
The square of 8 is: 64.00

## Result
program was implemented and executed.
