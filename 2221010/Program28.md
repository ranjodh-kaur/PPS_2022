## Program28: To write a program to swap two numbers without using third variable
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
**Output**:

Enter 1st number(a):3

Enter 2nd number(b):6

After swapping,The value of a is 6

After swapping,The value of b is 3
