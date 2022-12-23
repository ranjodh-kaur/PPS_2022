## Program19: To write a code using string copy function
```C
#include<stdio.h>

#include<string.h>

int main()
  
{
  
char a[]="I am a student of";
  
char b[]="Guru Nanak Dev Engineering";
  
strcpy(b,a);
  
printf("%s",a);
  
printf("\n%s",b);
  
return 0;
  
}
```
**Output**:
```C
I am student of

I am student of
