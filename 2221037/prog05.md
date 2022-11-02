## Program 5: Write a program to show use of if statements

```C
#include<stdio.h>

//program to use if statements

int main(){
	int x;
	printf("Enter a number : ");
	scanf("%d",&x);
	if(x%2 == 0) printf("%d is even\n",x);
	else printf("%d is odd\n",x);

	return 0;
}
```

### Output:
```
Enter a number : 44
44 is even
----------------------------
Enter a number : 55
55 is odd
```
