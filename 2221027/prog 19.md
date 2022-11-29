## Program 19: Use of float and double. (Tutorial 4)
```C
#include<stdio.h>
int main()
{
	float age1;
	double age2;
	printf("Please enter your age:");
	scanf("%f", &age1);
	printf("Enter your childs's age:");
	scanf("%lf",&age2);
	printf("age1=%f\n",age1);
	printf("age2=%lf",age2);
	return 0;
}
```
```
Output:Please enter your age:50
Enter your childs's age:20
age1=50.000000
age2=20.000000
```
