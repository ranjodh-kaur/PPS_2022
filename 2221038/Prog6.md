## Program 6: Write a program to show ascii character of a given code

```c

#include <stdio.h>

int main(){

    int x;

    printf("Enter a ascii value: ");

    scanf("%d",&x);

    printf("Character for ascii value %d: %c\n",x,(char)x);

    return 0;

}

```

### Output:

```

Enter a ascii value: 97

Character for ascii value 97: a

```

