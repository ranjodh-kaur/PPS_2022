## Write a program to illustarte the use of strcat function
```C
#include <stdio.h>
#include<string.h>
int main()
{
char a[50] = "Hey rangi ";
char b[50] = "Let go ";
strcat(a,b);
printf("%s\n",a);
return 0;
}
```
**Output:Hey rangi Let go**
