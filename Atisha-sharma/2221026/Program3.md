## Program 3 : Write a program to input two numbers using scanf() and add them
#include <stdio.h>

int main()

{

int a, b, sum;

printf("Enter two numbers: ");

scanf("%d %d", &a, &b);

//calculation sum
sum = a+b;

printf("%d + %d = %d' , a, b, sum);

return0;

}

## output: Enter two numbers:5

20

5+20=25
