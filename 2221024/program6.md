## Program for If Program

#include <stdio.h>

int main(){

int n1,n2,n3;

n1=57,n2=45,n3=10;

if (n1>n2 && n1>n3)

printf("%d",n1);

else {

    if(n2>n1 && n2>n3)
    
    printf("%d",n2);
    
    else {
    
        if(n3>n1 && n3>n2)
        
        printf("%d",n3);
        
}

}

}


**Output: 57**
