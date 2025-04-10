## EX-NO-6-Pseudo-Random-Number
### DATE: 10-04-2025
## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:
###### Start the program and import the required libraries.
###### Seed the random number generator using the current time(i.e) rand(time(0));
###### Get the number of randon number to generate.
###### Pass the value for number of iterations and print the numbers.
###### End the program.

## PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    printf("Pseudo-Random Number Generation using Standard Library\n");

    srand(time(0));

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated Random Numbers:\n");
    for(i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    printf("End of program.\n");

    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/a4a0e932-dc9e-4cd5-b873-98f5c4aa1e7f)

## RESULT:
The program to implement pseudo-random number generation using the standard library was successfully executed. The output displays a series of random numbers generated using the rand() function, seeded with the current time to ensure randomness on each run.
