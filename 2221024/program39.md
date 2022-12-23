## Write a program to illustrate the use of strcpy function.
```C
#include <stdio.h>
#include<string.h>
int main()
{
char a[50] = "BATMAN";
char b[50] = "THE AVENGERS";
strcpy(a,b);
printf("%s\n",a);
printf("%s",b);
return 0;	
}
```
**Output:THE AVENGERS
THE AVENGERS**
