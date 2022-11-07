## Program 2: Write a program to show operators

```c
#include<stdio.h>

int main(){
  int a=25,b=5;
  printf("A = %d,B = %d\n",a,b);
  printf("A + B = %d\n",a+b);
  printf("A - B = %d\n",a-b);
  printf("A * B = %d\n",a*b);
  printf("A / B = %d\n",a/b);
  printf("A mod B = %d\n",a%b);
  
  printf("A & B = %d\n",a & b);
  printf("A | B = %d\n",a & b);
  printf("~A = %d\n",~a);
  
  return 0;

  }

```

### Output:
```
A = 25,B = 5
A + B = 30
A - B = 20
A * B = 125
A / B = 5
A mod B = 0
A & B = 1
A | B = 1
~A = -26
```
