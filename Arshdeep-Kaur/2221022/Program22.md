## Program 22: Write a program to print FIBONACCI SERIES upto n numbers

#include<stdio.h>   

int main()    

{    

 int a=0,b=1;
 
 int c,i,number;    
 
 printf("Enter the number of elements:");  
 
 scanf("%d",&number); 
 
 printf("\n%d %d",a,b);   
 
 for(i=2;i<number;++i) 
 
 {    
 
  c=a+b;    
  
  printf(" %d",c);   
  
  a=b;    
  
  b=c;    
  
 }  
 
  return 0;  
  
 }    
 
 **OUTPUT:Enter the number of elements:10**
 
**0 1 1 2 3 5 8 13 21 34**
