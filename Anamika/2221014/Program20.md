## Program 20: Write a program to check if entered number is a prime number
#include <stdio.h>

int main()

{ int n, i, count = 0;

printf("Enter any number n:");

scanf("%d", &n);

for (i = 1; i <= n; i++)

{

  if (n % i == 0) 
  
     count++;
}

if (count == 2)

{

    printf("n is a Prime number");
}

else

{

     printf("n is not a Prime number");
}

return 0;

}

OUTPUT:Enter any number n:5

n is a Prime number
