## Program 34 : Write a program to check Palindrome String.
```C
#include<stdio.h>
#include<string.h>
int main()
{
	char string1[25];
	int i,j,k=1,length;
	printf("Enter the word:");
	scanf("%s",&string1);
	length=strlen(string1);
	j=length-1;
	for(i=0;i<length/2;i++,j--)
	{
		if(string1[i]!=string1[j])
		{
			k=0;
			break;
		}
	}
	if(k==1)
	{
		printf("Word is Palindromic");
	}
	else
	{
		printf("Word is not Palindromic");
	}
	return 0;
```
**Output :**
```C
Enter the word:mom
Word is Palindromic
