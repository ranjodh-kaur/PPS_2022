## Program 19:  Write a program to print number of ODD no.s between 98-146 using function

#include <stdio.h>

int odd();

int main()

{

    printf("Number of Odd no.s between 98 to 146 are: ");
    
    odd();
    
}

int odd()

{

    int count=0;
    
    int i;
    
    for(i=98;i<=146;i++)
    
    {
    
        if(i%2!=0)
        
        count++;
        
    }
    
    printf("%d\n",count);
    
    return 0;
    
}

**OUTPUT:Number of Odd no.s between 98 to 146 are: 24**
