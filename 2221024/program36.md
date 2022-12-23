## Write a program to print right angled star pattern.
```C

#include<stdio.h>
int main()
{
	int i,j;
	for (i=1;i<=4;i++)
	{for(j=0;j<i;j++)
	{
	printf("%c", '*');
	}
	printf("\n");
	}
	
	return 0;
	}
  ```
  ```
  Output:*
         **
         ***
         ****
