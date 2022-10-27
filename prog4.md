## Program 5 : Write a program to demonstrate the use of if else
```C
#include<stdio.h>
int main()
{
    int x;
    printf("enter a number :");
    scanf("%d",&x);
    if(x%2==0)
    printf("%d is even \n",x);
    else printf("%d is odd \n",x);
    return 0;
}
```
```
output: Enter a number: 44
44 is even
Enter a number : 45
45 is odd
```
