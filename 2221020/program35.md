## Program 35: Write a code to show the use of pointers.
```C
#include<stdio.h>

int main()
{
    int a=5;
    int* ptr=&a;
    printf("The address where a is stored is %x\n",ptr);
    printf("The value of a is %d",a);
    return 0;
	} 
```
```
output:
The value of a is 5
```
