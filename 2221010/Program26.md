## Program26: To write a program to find the factorial of a number
```C
#include<stdio.h>
int main()
{
	int num,fact=1,i;
	printf("Enter the number to find its factorial:");
	scanf("%d",&num);
	for(i=1;i<=num;i++)
	{
		fact=fact*i;
	}
	printf("The factorial of %d is %d", num,fact);
	
	return 0;
	}
  ```
  **Output**:
 Enter a number to find its factorial:5
 
 The factorial of 5 is 120
