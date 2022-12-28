## Program 37 : Write a program using user defined functions.
```C
#include <stdio.h>
int sum(int a, int b);         

int main()
{
    int a,b,c;

    printf("Enters two numbers: ");
    scanf("%d %d",&a,&b);

    c = sum(a, b);        
    printf("c= %d",c);

    return 0;
}
int sum(int x, int y)            
{
    int result;
    result = x+y;
    return result;                  
}
```
**Output :**
```C
Enters two numbers: 56 78
c= 134
