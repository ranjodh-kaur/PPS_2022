
## Program 29: Write a program to demonstrate for loop in C
```c
#include <stdio.h>

//Program to demonstrate for loop

int main(){
    int n;
    printf("Enter number to count to: ");
    scanf("%d",&n);

    for(int i=0; i<n; i++){
        printf("%d\t",i+1);
    }
    printf("\n");

    return 0;
}
```
## Output:
```
Enter number to count to: 10
1	2	3	4	5	6	7	8	9	10
```
