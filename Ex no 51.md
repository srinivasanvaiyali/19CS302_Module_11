# EX 51 C program to reverse a string.
## DATE:
## AIM:
To write a C program to reverse a string.

## Algorithm
1. Start
2. Accept a string from the user.
3. Determine the length of the string.
4. Initialize two pointers:- One at the beginning (i = 0).
5. One at the end (j = length - 1).
6. wap the characters at positions i and j.
7. Increment i and decrement j.
8. Repeat steps 5 and 6 until i is greater than or equal to j.

## Program:
```
/*
C program to reverse a string.
Developed by: SRINIVASAN V
RegisterNumber:  212222043008
*/
```
```
#include <stdio.h>
#include <string.h>

int main() {
    char str[100], reversed[100];
    int length, i;

    printf("Enter a string: ");
    scanf("%s", str);  // Reads a single word

    length = strlen(str);

    // Reverse manually
    for (i = 0; i < length; i++) {
        reversed[i] = str[length - i - 1];
    }
    reversed[length] = '\0'; // Null-terminate the reversed string

    printf("Reversed string: %s\n", reversed);
    
    return 0;
}
```

## Output:

<img width="378" height="201" alt="441038775-a5f48a4c-97a5-4f48-818c-9235da71bb17" src="https://github.com/user-attachments/assets/76046a9d-987a-42b2-96dc-fa91b2bc604f" />


## Result:
Thus the program was executed and the output was verified successfully.
