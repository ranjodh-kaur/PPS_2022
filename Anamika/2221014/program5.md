 ## program:5 write a program to find the largest number among three

#include<stdio.h>

int main()
{

int n1,n2,n3;

n1=56,n2=44,n3=10;
if(n1>=n2 && n1>=n3)

printf("n1 is the largest number");

if(n2>=n1 && n2>=n3)

printf("n2 is the largest number");

if(n3>=n1 && n2>=n3)

printf("n3 is the largest number");

return 0;

}

**Output* : n1 is the largest number**
