## Program 6: Write a program to input username and roll no

#include <stdio.h>

int main()

{

    char str[15];
    
    int n;
    
    printf("Enter your username\n");
    
    scanf("%s", &str);
    
    printf("Enter your roll no.\n");
    
    scanf("%d", &n);
    
    printf("Username =%s\n",str);
    
    printf("Roll no.=%d\n",n);
    
    return 0;
    
}

**OUTPUT: Enter your username**
**heretoconquer**
**Enter your roll no.**
**2221022**
**Username=heretoconquer**
**Roll no.=2221022**
