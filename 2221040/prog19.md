## Program 19: Write a program to use float and double datatypes and puts function
```
#include<stdio.h>
int main()
{
float m1;
double m2;
puts("Enter Father age");
scanf("%f",&m1);
puts("Enter Child age");
scanf("%lf",&m2);
printf("Father age=%f\n",m1);
printf("Child age=%lf\n",m2);
return 0;
}
```
**Output-Enter Father age
31
Enter Child age
3
Father age=31.000000
Child age=3.000000**
