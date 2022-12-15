## Program 10: Write a program to demonstrate do while loop
```c
#include <stdio.h>

//Program to use do while loop

int main(){
    int n,sq,ans;
    printf("Enter a number: ");
    scanf("%d",&n);
    sq = n*n;

    do {
        printf("Guess the square of %d: ",n);
        scanf("%d",&ans);
        if(ans!=sq)printf("Wrong,try again\n");
    } while (ans!=sq);

    printf("Correct!\n");

    return 0;
}
```
 
## Output:
```
Enter a number: 5
Guess the square of 5: 20
Wrong,try again
Guess the square of 5: 26
Wrong,try again
Guess the square of 5: 25
Correct!
```
