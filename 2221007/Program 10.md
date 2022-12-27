## Program 10 : Write a code to use continue statement 
```C
#include<stdio.h>
int main()
{
int i=0;
while(i<10)  
{
if (i==4)
{
i++;
continue;
}
printf(%d\n,i);
i++;
}
return 0;
}

## Output: 0 1 2 3 4 5 6 7 8 9
