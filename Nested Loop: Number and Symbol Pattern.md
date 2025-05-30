Nested Loop: Number and Symbol Pattern Printer in C

Print @ symbols for (n - i) positions, where n is the total number of rows.
## Aim
To write a C program that prints the following specific pattern using nested loops:

1@@@@1  
12@@@21  
123@@321  
1234@4321  
1234554321  
## Algorithm
Initialize variables i and j.

Use nested loops to iterate over rows and columns.

In each row:

Print numbers in ascending order from 1 to i.

Print numbers in descending order from i to 1.

## Program
```
#include <stdio.h>

int main() {
    int i, j;
    for (i = 1; i <= 5; i++) {
        for (j = 1; j <= i; j++) {
            printf("%d", j);
        }
        for (j = 1; j <= 5 - i; j++) {
            printf("@");
        }
        for (j = i; j >= 1; j--) {
            printf("%d", j);
        }
        printf("\n");
    }
    return 0;
}
```


## Output
Sample Output 1:
1@@@@1
12@@@21
123@@321
1234@4321
1234554321

Sample Output 2:
1@@@@1
12@@@21
123@@321
1234@4321
1234554321


## Result
Program was implemented and executed.
