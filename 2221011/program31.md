##  Write a program to swap two variable using a temporary variable
``` 
#include <stdio.h>
int main()
{
int n1,n2;
printf("Enter first number -> ");
scanf("%d",&n1);
printf("Enter second number -> ");
scanf("%d",&n2);
int temp = n1;
n1 = n2;
n2 = temp;
printf("\nAfter swapping:\n");
printf("First number -> %d\n",n1);
printf("Second number -> %d\n",n2);
return 0;
}
```
**Output:
Enter first number -> 66
Enter second number -> 99
After swapping:
First number -> 99
Second number -> 66**
