## Program 13: Write a program to illustrate the use of switch case statement
```   
#include<stdio.h>
int main()
{
    int i,j;
    char op;
 printf("Choose an operator (+,-,*,/)\n");
 scanf("%c",&op);
 printf("Enter two numbers on which u want to perform the operation\n");
 scanf("%d %d" , &i,&j);
switch(op)
{
	case '+':
		printf("i+j = %d\n",i+j);
		break;
	case '-':
		printf("i-j = %d\n",i-j);
		break;
	case '*':
		printf("i*j = %d\n",i*j);
		break;
	case '/':
		printf("i/j = %d\n",i/j);
		break;
	default:
		printf("Sorry, invalid request");
	}
 return 0;
}
Output: Choose an operator (+,-,*,/)
-
Enter two numbers on which u want to perform the operation
5
2
i-j = 3

