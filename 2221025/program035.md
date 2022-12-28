## Program 35 : Write a program for swapping using third variable.
```C
#include<stdio.h>
int main()
{

int a,b,c;
printf("Enter the value of a");
scanf("%d",&a);
printf("Enter the value of b");
scanf("%d",&b);
c=a;
a=b;
b=c;
printf("a=%d\nb=%d",a,b);
return 0;
}
```
**Output :**
```C
Enter the value of a 45
Enter the value of b 67
a=67
b=45
