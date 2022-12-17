## Program 11: Write a program to illustrate the use of break
```C
include<stdio.h>
int main()
{
int a,i=0;
printf("Enter the last number of serial counting");
scanf("%d", &a);
while(i<=a)
{
printf("%d\n",i);
if(i>a)
break;
i++;
}
return 0;
}
```
```output:
0
1
2
3
4
5
6
7
8
9
10
