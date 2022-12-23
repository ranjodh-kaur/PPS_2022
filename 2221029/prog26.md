## Program 26: Write a program to show the factorial of a given number
```
#include <stdio.h>
int fact(int n)
{
if(n<=1)return 1;
else return fact(n-1)*n;
}
int main()
{
int n;
printf("Enter a number: ");
scanf("%d",&n);
printf("Factorial of %d = %d\n",n,fact(n));
return 0;
}
```
***Output: Enter a number: 9 Factorial of 9 = 362880***
