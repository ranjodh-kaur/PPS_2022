## Program 9: Write a program to show the use of while loop

```c
#include <stdio.h>

//Program to use while loop

int main(){
    int n,sum=0;
    printf("Enter a number: ");
    scanf("%d",&n);

    while(n!=0){
        sum+=n%10;
        n/=10;
    }

    printf("Sum of digits: %d\n",sum);

    return 0;
}
```

### Output:
```
Enter a number: 4096
Sum of digits: 19
```
