## Program 13: Write a program to use switch statement

```c
#include <stdio.h>

int main(){
    int i;
    printf("Enter 1 for fan,2 for light,3 for ac, 4 for heater : " );
    scanf("%d",&i);
    switch(i){
        case 1:
            printf("Fan On\n");
            break;
        case 2:
            printf("Light On\n");
            break;
        case 3:
            printf("AC On\n");
            break;
        case 4:
            printf("Heater On\n");
            break;
        default:
            printf("Invalid Input\n");
            break;
    }

    return 0;
}
```
## Output:
```
Enter 1 for fan,2 for light,3 for ac, 4 for heater : 4
Heater On
Enter 1 for fan,2 for light,3 for ac, 4 for heater : 3
AC On
Enter 1 for fan,2 for light,3 for ac, 4 for heater : 9
Invalid Input
```
