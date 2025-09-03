# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:03/09/2005
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1. Start the program.
2. Declare three variables a, b, c of type float to store fraction numbers.
3. Read the values of a, b, and c from the user.
4. Use the conditional operator (?:) to find the smallest among the three: 
5. Stop the program.  

## Program:
#include <stdio.h>

int main() {
    float a, b, c, min;

    // Input three fraction numbers
    printf("Enter three fraction numbers: ");
    scanf("%f %f %f", &a, &b, &c);

    // Using conditional operator
    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("The minimum number is: %.2f\n", min);

    return 0;
}

## Output:

<img width="1445" height="582" alt="image" src="https://github.com/user-attachments/assets/361d9294-66e5-45da-99fd-e534d8dda314" />


## Result:
Thus the program was executed and the output was verified successfully.
