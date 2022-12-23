## Write a code by using Break and Continue

#include <stdio.h>

int main() 

{

int i = 0;

while (i < 10) 

{

if (i == 4) 

{

i++;

continue;

}

if (i ==7)

{

break;

}

printf("%d\n", i);

i++;

} 

return 0;

}

 **Output= 1 
           2 
           3 
           5
           6**
