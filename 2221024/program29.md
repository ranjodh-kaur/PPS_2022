## Program 29: Write a program to check if a number is palindromic
```
#include <stdio.h>
int reverse(int n)
{
int rev=0;
while(n>0)
{
rev = rev*10 + n%10;
n/=10;
}
return rev;
}
int isPalindrome(int n)
{
if(reverse(n) == n) return 1;
return 0;
}
int main()
{
int n;
printf("Enter a number to check -> ");
scanf("%d",&n);
if(isPalindrome(n))
{
printf("%d is a palidromic number\n",n);
}
else
{
printf("%d is not a palidromic number\n",n);
}
return 0;
}
```
**Output:Enter a number to check -> 393
393 is a palidromic number**

