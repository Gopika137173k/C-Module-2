## Functions: Factorial Calculator in C (Using Function)
## Aim
To write a C program that calculates the factorial of a given number using a user-defined function.

## Algorithm
Start the program.

Declare the function fact().

In the main() function, call the fact() function.

In the fact() function:

a. Declare variables i, N, and fact (initialized to 1).

b. Read an integer N from the user.

c. Use a for loop from 1 to N:

Multiply fact by i in each iteration.

d. After the loop, print the factorial value.

End the program.

## Program

```
#include <stdio.h>
int fact(int N) {
    int fact = 1;
    for (int i = 1; i <= N; i++) {
        fact *= i; // Multiply fact by i in each iteration
    }
    return fact;
}

int main() {
    int N;
   
    printf("Enter a number: ");
    scanf("%d", &N);
    printf("Factorial of %d is: %d\n", N, fact(N));
    
    return 0;
}

```


## Output

Sample Output 1
Enter a number: 4
Factorial of 4 is: 24

Sample Output 2
Enter a number: 7
Factorial of 7 is: 5040

## Result
Program was implemented and executed.
