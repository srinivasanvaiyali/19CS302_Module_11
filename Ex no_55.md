# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1. Start
2. Define a function findSquare(num) that takes an integer argument.
3. Inside the function, compute num * num and display the result.
4. In the main() function:
       *Accept an integer input from the user.
       *Call findSquare(number) with the input value.
5. End

## Program:
```
/*
C program to find a square of number using function with arguments without return type.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008  
*/
```
```
#include <stdio.h>

void findSquare(int num) {
    printf("Square of %d is: %d\n", num, num * num);
}

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    
    findSquare(number);
    
    return 0;
}
```


## Output:
<img width="422" height="201" alt="441054047-417382e7-5233-4f85-af71-e0b854b57f79" src="https://github.com/user-attachments/assets/e9add0ff-7ca2-43ef-b3f9-d5ed16c1601a" />



## Result:
Thus the program was executed and the output was verified successfully.
