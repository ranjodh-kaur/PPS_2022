## Program 3: Write a program to get user input

```C
#include<stdio.h>

int main(){
    char usr[20];
    int roll;
    printf("Enter username -> ");
    scanf("%s",usr);
    printf("Enter Roll number -> ");
    scanf("%d",&roll);

    printf("\nUsername -> %s\n",usr);
    printf("Password -> %d\n",roll);

    return 0;
}

```

### Output:
```
Enter username -> Devesh
Enter Roll number -> 2221037

Username -> Devesh
Password -> 2221037
```
