## Task

# Write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

## Note

There is not built in max function in C. Code that will be reused is often put in a separate function, e.g. int max(x, y) that returns the greater of the two values.

## Input Format

Input will contain four integers - a,b,c,d , one on each line.

## Output Format

Print the greatest of the four integers.
Note: I/O will be automatically handled.


# AIM:
To write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

# Algorithm:

1. Start
2. Accept four integer inputs: a, b, c, and d.
3. Initialize max with a.
4. Compare max with b:
   If b is greater than max, update max = b.
5. Compare max with c:
   If c is greater than max, update max = c.
6. Compare max with d:
   If d is greater than max, update max = d.
7. Return max as the largest number.
8. End
# PROGRAM:
```
#include<stdio.h>
int compare(int a[4])
{
    int max=a[0];
    for(int i=0;i<4;i++)
    {
        if(a[i]>max)
        max=a[i];
    }
    return max;
}
int main()
{
    int a[4];
    for(int i=0;i<4;i++)
    scanf("%d",&a[i]);
    int d= compare(a);
    printf("%d",d);
}
```
# OUTPUT:
<img width="814" height="374" alt="441039616-aba6d6ba-c7c3-4607-9f04-a740cafd9845" src="https://github.com/user-attachments/assets/2dc475e3-3e0f-4e8a-9440-deb2cc89620c" />

# RESULT:
Thus, the program is executed and verified successfully.
