##  Write a program to perform linear search
```c 
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
 **Output:Enter size of array
5
Enter elements:
Enter element at index 0 -> 85
Enter element at index 1 -> 54
Enter element at index 2 -> 56
Enter element at index 3 -> 92
Enter element at index 4 -> 15
Enter element to search -> 45
Entered array is :
85	54	56	92	15	
Location of 45 in array = 0**
