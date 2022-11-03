## Program 4: Write a program to display operators in C

```C
#include<stdio.h>

int main(){
	int a=50,b=5;

	printf("A = %d\n B = %d\n\n",a,b);
	printf("---- Arithmatic Operators ----\n");
	printf("A + B = %d (Addition Operator)\n",a+b);
	printf("A - B = %d (Subtraction Operator\n",a-b);
	printf("A * B = %d (Multiplication Operator)\n",a*b);
	printf("A / B = %d (Division Operator)\n",a/b);
	printf("A mod B = %d (Remainder operator)\n",a%b);

	printf("---- Bitwise Operators ----\n");
	printf("a = %d\n",a);
	printf("b = %d\n",b);
    	printf("a & b = %d  (Bitwise and)\n",a&b);
    	printf("a | b = %d  (Bitwise or)\n",a|b);
    	printf("~a = %d  (Bitwise not)\n",~a);

	printf("---- Conditional Operator ----\n");
	(a>b)?printf("a is greater\n"):printf("b is greater\n");

	return 0;
}
```

### Output:
```
A = 50
 B = 5

---- Arithmatic Operators ----
A + B = 55 (Addition Operator)
A - B = 45 (Subtraction Operator
A * B = 250 (Multiplication Operator)
A / B = 10 (Division Operator)
A mod B = 0 (Remainder operator)
---- Bitwise Operators ----
a = 50
b = 5
a & b = 0  (Bitwise and)
a | b = 55  (Bitwise or)
~a = -51  (Bitwise not)
---- Conditional Operator ----
a is greater
```
