Nested Loop: Number and Symbol Pattern Printer in C
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

Print @ symbols for (n - i) positions, where n is the total number of rows.

Print numbers in descending order from i to 1.

## Program
 ```
#include <stdio.h>

int main() {
    int n = 5; 
  
    for (int i = 1; i <= n; i++) {
        
        for (int j = 1; j <= i; j++) {
            printf("%d", j);
        }
        for (int j = 1; j <= (n - i); j++) {
            printf("@");
        }
        for (int j = i; j >= 1; j--) {
            printf("%d", j);
        }
        printf("\n");
    }

    return 0;
}
```

## Output

Sample Output 1 (with n = 5):
1@@@@1
12@@@21
123@@321
1234@4321
1234554321

Sample Output 2 (with n = 4):
1@@@1
12@@21
123@321
1234321

## Result
program was implemented and executed.
