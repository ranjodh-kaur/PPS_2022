## Program 33: Write a program to swap two numbers without third variable.
```C
#include<stdio.h>
int main()
{
	int a,b;
	printf("Enter 1st number(a): ");
	scanf("%d",&a);
	printf("Enter 2nd number(b): ");
	scanf("%d",&b);
	a=a+b;
	b=a-b;
	a=a-b;
	printf("After swapping,The value of a is %d.\n",a);
	printf("After swapping,The value of b is %d",b);
	return 0;
}
```
```
output:Enter 1st number(a): 5
Enter 2nd number(b): 4
After swapping,The value of a is 4.
After swapping,The value of b is 5
```
