# EX 18 C program to find frequency of a character in the given input.
## DATE:03/09/2025
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1. Start the program
2. Declare a string and a character variable
3. Read the string and the character from the user
4. Traverse the string and count the occurrences of the given character. 
5. Display the frequency of the character.  

## Program:
#include <stdio.h>

int main() {
    char str[100], ch;
    int i, count = 0;

    printf("Enter a string: ");
    scanf("%[^\n]", str);

    printf("Enter a character to find frequency: ");
    scanf(" %c", &ch);

    for (i = 0; str[i] != '\0'; i++) {
        if (str[i] == ch) {
            count++;
        }
    }

    printf("Frequency of '%c' = %d\n", ch, count);

    return 0;
}


## Output:

<img width="1556" height="677" alt="image" src="https://github.com/user-attachments/assets/ff68c3ab-7514-4880-a785-b51f64afd9bc" />


## Result:
Thus the program was executed and the output was verified successfully.
