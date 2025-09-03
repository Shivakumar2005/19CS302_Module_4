# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:03/09/2025
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1. Start the program.
2. Declare a character array to store the string.
3. Read the string from the user.
4. Traverse each character and if it is uppercase ('A'–'Z'), convert it to lowercase by adding 32. 
5. Display the converted string.  

## Program:
#include <stdio.h>

int main() {
    char str[100];
    int i;

    printf("Enter a string: ");
    scanf("%[^\n]", str);

    for (i = 0; str[i] != '\0'; i++) {
        if (str[i] >= 'A' && str[i] <= 'Z') {
            str[i] = str[i] + 32;
        }
    }

    printf("String in lowercase: %s\n", str);

    return 0;
}


## Output:

<img width="1488" height="661" alt="image" src="https://github.com/user-attachments/assets/d814f229-f511-43ea-8b5a-0931e8d8995b" />


## Result:
Thus the program was executed and the output was verified successfully.
