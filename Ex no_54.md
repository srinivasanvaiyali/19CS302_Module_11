# EX 54 D program to print all the letters of the English alphabet.
# DATE:
# AIM:
To write a C program to print all the letters of the English alphabet.

# Algorithm:
1. Start
2. Initialize a character variable ch with 'A'.
3. Loop from 'A' to 'Z':
 * Print the character.
 * Print a space after each character.
4. End the loop once 'Z' is printed.
5. End
   
# Program:
```
#include <stdio.h>

int main() {
    char ch;
    
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
    
    return 0;
}
```
# Output:
<img width="567" height="153" alt="441046326-19dc5de0-1868-49eb-ae01-387170e6b6bc" src="https://github.com/user-attachments/assets/857bf992-0038-49ff-88f2-b15dafc75bae" />

# Result:
Thus the program was executed and the output was verified successfully.
