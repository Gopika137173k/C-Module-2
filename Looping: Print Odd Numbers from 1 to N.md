## Looping: Print Odd Numbers from 1 to N in C
## Aim
To write a C program that prints all odd numbers from 1 to n, where n is an integer input by the user.

## Algorithm
Declare variables n and i.

Read the value of n from the user.

Iterate i from 1 to n using a for loop.

Inside the loop:

If i is odd, print its value.

Increment i to skip the next even number (can also increment by 2 for simplicity).

## Program
```
#include <stdio.h>
int main() {
    int n;
    printf("Enter an integer n: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; i++) {
        // Check if i is odd
        if (i % 2 != 0) {
            printf("%d ", i);
        }
    }

    printf("\n"); 
    return 0;
}
```

## Output

Sample Output 1:
Enter an integer n: 6
1 3 5

Sample Output 2:
Enter an integer n: 13
1 3 5 7 9 11 13

## Result
program was implemented and executed.
