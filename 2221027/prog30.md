## Program 30: Write a program to swam two numbers using third variable.
```C
#include<stdio.h>

int main()
{
    int a=15,b=20,c;
    printf("Current value of a is %d\n",a);
    printf("current value of b is %d\n",b);
    c=b;
    b=a;
    a=c;
    printf("After swapping, the value of a is %d\n",a);
    printf("After swapping, the value of b is %d",b);
	return 0;
	}
```
```
Output:Current value of a is 15
current value of b is 20
After swapping, the value of a is 20
After swapping, the value of b is 15
```
