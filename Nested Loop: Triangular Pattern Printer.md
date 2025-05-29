## Nested Loop:Triangular Pattern Printer in C
## Aim
To write a C program that prints a triangular pattern of $ symbols using nested loops based on a user-defined value n.

## Algorithm
Declare variables n, i, and j.

Read the value of n from the user.

Use a for loop to iterate i from n to 1.

Inside the outer loop, use another for loop to iterate j from 1 to i and print "$".

After each inner loop, print a newline character (\n) to move to the next line.

## Program
```
#include <stdio.h>

int main() {
    int n;
    printf("Enter the value of n: ");
    scanf("%d", &n);
    for (int i = n; i >= 1; i--) {
        for (int j = 1; j <= i; j++) {
            printf("$");
        }
        printf("\n");
    }

    return 0;
}
```
## Output
Sample Output 1:
Enter the value of n: 5
$$$$$
$$$$
$$$
$$
$

Sample Output 2:
Enter the value of n: 3
$$$
$$
$

## Result

Program was implemented and executed.
