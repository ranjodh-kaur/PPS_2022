## Program27: To check a number entered is whether palindrome or not
```C
#include<stdio.h>
int main()
{
	int num,sum=0,q,rem;
	printf("Enter the number here to check if it is palindromic: ");
	scanf("%d",&num);
	q=num;
	while(q>0)
	{
		rem=q%10;
		sum=sum*10+rem;
		q=q/10;		
		}
	if(sum==num)
	printf("The number entered is Palindromic.");
	else
	printf("The number entered is Not Palindromic.");
	return 0;
}
```
**Output**:

Enter a number here to check if it is palindromic:565

The number entered is palindromic.
