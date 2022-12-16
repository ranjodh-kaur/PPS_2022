## Program 10: Write a program to print odd numbers between 1 to 10 using CONTINUE

#include<stdio.h>  

int main()

{  

int i=1;

for(i=1;i<=10;i++)

{      
    
if(i%2==0)

continue; 

printf("%d \n",i);   

}

return 0;  

}    

**OUTPUT:1**

**3** 

**5**

**7**

**9**
