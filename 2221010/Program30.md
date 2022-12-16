## Program30: To write a code to display the use of pointers
```C
#include<stdio.h>

int main()
{
    int a=9;
    int* ptr=&a;
    printf("The address where a is stored is %x\n",ptr);
    printf("The value of a is %d",a);
    return 0;
	} 
  ```
  **Output**:
  
  The address where a is stored is 83dde59c
  
  The value of a is 9
