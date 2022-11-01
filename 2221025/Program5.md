## Program 5 : Write a program using conditional operators
/*T denotes percentage inn 12th standard
P denotes percentage in 10th standard*/
#include<stdio.h>
int main()
{
int T=90,P=90,c;
c=(T>80&&P>80)?1000:(P>80)?500:0;
printf("%d",c);
return 0;
}
