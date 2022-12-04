## Program 14: Write a program to compare two strings

#include <stdio.h>

#include <string.h>

int main()

{

  char s1[20] = "Archi";
  
  char s2[20] = "archi";
 
  if (strcmp(s1, s2) == 0) 
  
  {
  
    printf("string 1 and string 2 are equal");
    
  }
  
  else 
  
  {
  
    printf("string 1 and 2 are different");
    
  }
  
}

**OUTPUT:string 1 and 2 are different**
