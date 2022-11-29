## Program13: To write a program to get character variable of ASCII value
```C
#include <stdio.h>

int main() 

{  

int i;

printf("Enter a ASCII value: ");

scanf("%d", &i);  

printf("Charcter value of %d = %c", i, i);

return 0;

}
```
**Output**:  
```C
Enter a ASCII value:71

Character value of 71 = G
