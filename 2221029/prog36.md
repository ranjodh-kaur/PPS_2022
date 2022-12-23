## Program36: To write a program to perform linear search
```
#include <stdio.h>
int main(){
    int len,target,ind;
    printf("Enter size of array\n");
    scanf("%d",&len);
    int arr[len];
    printf("Enter elements:\n");
    for(int i=0;i<len;i++){
        printf("Enter element at index %d -> ",i);
        scanf("%d",&arr[i]);
    }
    printf("Enter element to search -> ");
    scanf("%d",&target);
    printf("\nEntered array is :\n");
    for(int i=0;i<len;i++){
        printf("%d\t",arr[i]);
    }
    printf("\n");
    for(int i=0;i<len;i++){
        if(arr[i] == target)ind=i;
    }
    printf("\nLocation of %d in array = %d\n",target,ind);
}
```
Output:

Enter size of array

5

Enter elements:

Enter elements at index 0 ->1

Enter elements at index 1 ->2

Enter elements at index 2 ->3

Enter elements at index 3 ->4

Enter elements at index 4 ->5

Enter element to search ->4

Entered array is :

1 2 3 4 5

location of 4 in array = 3
