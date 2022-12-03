## Program 2: Write a program sohw bitwise operators

```C
#include<stdio.h>

int main(){
	int a = 17,b=23;

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
a = 17
b = 23
a & b = 17  (Bitwise and)
a | b = 23  (Bitwise or)
~a = -18  (Bitwise not)
```
