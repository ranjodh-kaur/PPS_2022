## Program 6: Write a program to show the use of bitwise operators

```c
#include <stdio.h>

//Program to demonstrate bitwise operators

int main(){
    int a,b;
    printf("Enter a number: ");
    scanf("%d",&a);
    printf("Enter another number: ");
    scanf("%d",&b);

    printf("a = %d\n",a);
    printf("b = %d\n",b);
    printf("a & b = %d  (Bitwise and)\n",a&b);
    printf("a | b = %d  (Bitwise or)\n",a|b);
    printf("~a = %d  (Bitwise not)\n",~a);


    return 0;
}
```

### Output:
```
Enter a number: 5
Enter another number: 9
a = 5
b = 9
a & b = 1  (Bitwise and)
a | b = 13  (Bitwise or)
~a = -6  (Bitwise not)
```
