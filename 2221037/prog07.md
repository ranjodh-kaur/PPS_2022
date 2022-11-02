## Program 7: Write a program to show the use of if statements

```c
#include <stdio.h>

//Program to demonstrate the conditional operator

int main(){
    int n;
    printf("Enter any number: ");
    scanf("%d",&n);

    (n>=0)?(n==0?printf("n is zero\n"):printf("n is positive\n")):printf("n is negetive\n");
    return 0;
}
```

### Output:
```
Enter any number: -5
n is negetive
```
```
Enter any number: 6543
n is positive
```
```
Enter any number: 0
n is zero
```
