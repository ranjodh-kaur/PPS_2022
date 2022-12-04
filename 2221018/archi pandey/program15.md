## Program 15: Write a program to concat two strings

#include <stdio.h>

#include <string.h>

int main () 

{

  char string1[10] = "Archi";
     
  char string2[10] = "Pandey";
     
  strncat(string1,string2,4);
     
  printf("Concatenated string: %s", string1);

     
}

**OUTPUT:Concatenated string: Archi Pandey**
