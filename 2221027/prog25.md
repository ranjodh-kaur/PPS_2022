## Program25: Write a program to display Fibonacci series.
```C
#include<stdio.h>
int main()
{
   int n1=0,n2=1,n3,i,terms;
   printf("Enter the number of terms: ");
   scanf("%d",&terms);
   printf("%d\n",n1);
   printf("%d\n",n2);
   for(i=3;i<=terms;i++)
   {
   	n3=n1+n2;
   	printf("%d\n",n3);
   	n1=n2;
   	n2=n3;
   }
   return 0;
}
```
```C
Output:Enter the number of terms: 15
0
1
1
2
3
5
8
13
21
34
55
89
144
233
377
```
