## Program 16: Write a program to find the sum of all elements of an array
#include <stdio.h>

int main()

{

int ar[100];

int i, n, sum=0;

printf("Input the number of elements to be stored in the array :");

scanf("%d",&n);

printf("Input %d elements in the array :\n",n);

for(i=0;i<n;i++)

{

printf("%d : ",i);

scanf("%d",&ar[i]);

}

for(i=0; i<n; i++)

{

sum=sum+ar[i];

}

printf("Sum of all elements stored in the array is : %d\n\n", sum);

}

OUTPUT:Input the number of elements to be stored in the array :4

Input 4 elements in the array :

0 : 34

1 : 2

2 : 29

3 : 22

Sum of all elements stored in the array is : 87
