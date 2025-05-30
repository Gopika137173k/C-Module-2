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
    int n, i;

    printf("Enter the value of n: ");
    scanf("%d", &n);

    for (i = 1; i <= n; i += 2) {
        printf("%d ", i);
    }

    return 0;
}
```


## Output
Sample Output 1:
Enter the value of n: 10
1 3 5 7 9

Sample Output 2:
Enter the value of n: 7
1 3 5 7


## Result
Program was implemented and executed.
