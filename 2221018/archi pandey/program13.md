## Program 13: Write a program to find length of user's name

#include <stdio.h>

#include <string.h>

int main() 

{

  char string1[30];
  
  printf("Enter your first name\n");
  
  scanf("%s", &string1);
  
  printf("Length: %ld", strlen(string1));
  
  return 0;
  
}

**OUTPUT:Enter your first name**

**Archi**

**Length: 5**
