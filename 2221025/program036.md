## Program 36 : Write a program to swap numbers using 2 variables.
```C
#include <stdio.h>
 
int main()
{
    int x, y;
    printf("Enter Value of x ");
    scanf("%d", &x);
    printf("\nEnter Value of y ");
    scanf("%d", &y);
 
    int temp = x;
    x = y;
    y = temp;
 
    printf("\nAfter Swapping: x = %d, y = %d", x, y);
    return 0;
}
```
**Output :**
```C
Enter Value of x  23

Enter Value of y 12

After Swapping: x = 12, y = 23
