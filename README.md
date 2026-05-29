# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    // Seed the random number generator
    srand(time(0));

    // Get number of random numbers
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated Pseudo-Random Numbers:\n");

    // Generate and print random numbers
    for(i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}

```

# OUTPUT:
<img width="940" height="562" alt="image" src="https://github.com/user-attachments/assets/80cf210d-e31b-4547-a91b-dcbcff44880d" />


# RESULT:
Thus, the program for generating pseudo-random numbers using the standard library function was successfully implemented and executed.
