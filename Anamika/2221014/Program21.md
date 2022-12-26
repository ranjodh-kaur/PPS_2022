## Program 21: Write a program to check if number is palindrome or not
#include<stdio.h>

int main()

{

int num,mod,sum=0,b;

printf("enter the number=");

scanf("%d",&num);

b=num;

while(num>0)

{

mod=num%10;

sum=(sum*10)+mod;

num=num/10;

}

if(b==sum)

printf("It is a palindrome number ");

else

printf("Not a palindrome number");

return 0;

}

OUTPUT:Enter the number=191

It is a palindrome number

Enter the number=1000

Not a palindrome number
