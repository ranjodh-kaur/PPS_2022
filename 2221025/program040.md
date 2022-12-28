## Program 40 : Write a program using pointers.
```C
#include <stdio.h>
void ashmeet()
{
    int var = 20;
	int* ptr;
	ptr = &var;
	printf("Value at ptr = %p \n", ptr);
    printf("Value at var = %d \n", var);
    printf("Value at *ptr = %d \n", *ptr);
}
int main()
{
    ashmeet();
    return 0;
}
```
**Output :**
```C
Value at ptr = 000000000062FDE4
Value at var = 20
Value at *ptr = 20
