## Program 9: Write a program to print Day Name by input of day number of the week

#include <stdio.h>

int main()

{

int day=6;

printf("Enter the day no. of the week\n");

scanf("%d", &day);

switch (day) 

{

  case 1:
  
    printf("Monday");
    
    break;
    
  case 2:
  
    printf("Tuesday");
    
    break;
    
  case 3:
  
    printf("Wednesday");
    
    break;
    
  case 4:
  
    printf("Thursday");
    
    break;
    
  case 5:
  
    printf("Friday");
    
    break;
    
  case 6:
  
    printf("Saturday");
    
    break;
    
  case 7:
  
    printf("Sunday");
    
    break;
    
}

}


**OUTPUT: Enter the day no. of the week**

**5**

**Friday**
