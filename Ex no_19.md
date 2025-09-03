# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:03/09/2025
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Start the program.
2. Declare an integer variable and read its value from the user.
3. Perform left shift operation (num << 1) and store the result.
4. Perform right shift operation (num >> 1) and store the result. 
5. Display the results of both left and right shift operations.  

## Program:
#include <stdio.h>

int main() {
    int num, leftShift, rightShift;

    printf("Enter an integer: ");
    scanf("%d", &num);

    leftShift = num << 1;
    rightShift = num >> 1;

    printf("Original number: %d\n", num);
    printf("After left shift: %d\n", leftShift);
    printf("After right shift: %d\n", rightShift);

    return 0;
}


## Output:

<img width="1436" height="638" alt="image" src="https://github.com/user-attachments/assets/c7dc2a7b-1045-49da-b13b-3dd8cf3e94d0" />


## Result:
Thus the program was executed and the output was verified successfully.
