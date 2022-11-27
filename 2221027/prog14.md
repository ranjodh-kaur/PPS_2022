## Program 14: Write a program to illustrate the use of goto statement
```
#include<stdio.h>
int main()
{
	int i;
	for(i=0;i<=10;i++){
		if(i==5){
			goto avleen;
		}
		printf("%d\n",i);
	}
	avleen: printf("Hi you are out of the loop");
	return 0;
}
```
``` 
Output: 0
1
2
3
4
Hi you are out of the loop
```
