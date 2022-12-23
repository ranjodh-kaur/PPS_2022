## Program29: To write a program to swap two numbers using third variable
```C
#include<stdio.h>

int main()
{
    int a=40,b=20,c;
    printf("Current value of a is %d\n",a);
    printf("Current value of b is %d\n",b);
    c=b;
    b=a;
    a=c;
    printf("After swapping, the value of a is %d\n",a);
    printf("After swapping, the value of b is %d",b);
	return 0;
  }
  ```
  **Output**:
  
  Current value of a is 40
  
  Current value of b is 20
  
  After swapping, the value of a is 20
  
  After swapping, the value of b is 40
  
