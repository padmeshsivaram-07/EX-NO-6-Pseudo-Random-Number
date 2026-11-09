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

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Pseudo Random Numbers are:\n");

    for(i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```

# OUTPUT:
<img width="460" height="255" alt="Screenshot 2026-11-09 170445" src="https://github.com/user-attachments/assets/1b2364d5-d1b6-4736-8a07-7c37ff0e2e29" />


# RESULT:
Thus, the C program to implement pseudo-random number generation using the standard library was successfully executed, and the random numbers were generated and displayed.
