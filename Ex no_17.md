# EX 17 C Program to compare two strings without using strcmp().
## DATE:03/09/2025
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Start the program.
2. Declare two character arrays to store strings.
3. Read both strings from the user.
4. Compare the strings character by character until a mismatch or end of string occurs. 
5. Display whether the strings are equal or which one is greater.  

## Program:
#include <stdio.h>

int main() {
    char str1[100], str2[100];
    int i = 0, flag = 0;

    printf("Enter first string: ");
    scanf("%s", str1);

    printf("Enter second string: ");
    scanf("%s", str2);

    while (str1[i] != '\0' && str2[i] != '\0') {
        if (str1[i] != str2[i]) {
            flag = 1;
            break;
        }
        i++;
    }

    if (flag == 0 && str1[i] == '\0' && str2[i] == '\0')
        printf("Strings are equal\n");
    else if (str1[i] > str2[i])
        printf("First string is greater\n");
    else
        printf("Second string is greater\n");

    return 0;
}


## Output:

<img width="1600" height="665" alt="image" src="https://github.com/user-attachments/assets/e9d3c6f8-464f-4d1a-b2da-c4772937adf3" />


## Result:
Thus the program was executed and the output was verified successfully.
