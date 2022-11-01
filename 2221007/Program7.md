### Program 4 : Write a program for finding greatest between 3 numbers
```C
#include<stdio.h>
int main()
{
int a=10,b=20,c=30;
if((a>b) && (a>c))
{
printf("a is greater");
}
else if(b>c)
{
printf("b is greater");
}
else 
{
printf("c is greater");
}
return 0;
}
```
Output : c is greater
