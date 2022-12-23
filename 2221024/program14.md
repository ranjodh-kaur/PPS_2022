## Write a code by using goto statement
#include <stdio.h>

  int main()
  
{

    int i=26;
    
    if (i % 2 == 0)
       
        goto even; 
   
   else
        
        goto odd; 
           
even:
   
   printf("%d is even", i);
    
    return; 

odd:
    
    printf("%d is odd", i);

}

**Output: 26 is even**
