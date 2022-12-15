## Program 37: Write a program to illustrate the use of strcmp function.
```C
#include<stdio.h>
int main()
{
  char a[]= "world";
  char b[]= "world";
  int c= strcmp(b,a);
if(c==0)
printf("strings are equal");
else
printf("strings are not equal");
  return 0;
}
```
```
Output:strings are equal
```
