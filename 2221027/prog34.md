## Program 34: Write a program to illustrate the use of strcpy function.
```C
#include <stdio.h>
#include<string.h>
int main()
{
char a[50] = "The fox";
char b[50] = "jumped";
strcpy(a,b);
printf("%s\n",a);
printf("%s",b);
return 0;	
}
```
```
Output:jumped
jumped
```
