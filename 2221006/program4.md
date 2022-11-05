## Program 4: Write a program to show conditional operator
```c
#include<stdio.h>

int main(){
	int m;
	printf("Enter marks : ");
	scanf("%d",&m);
	char ans[20] = m>50?"Pass":"Fail";
        printf("%s",ans);
	return 0;
}
```
### Output:
```
Enter marks : 85
Pass
```
