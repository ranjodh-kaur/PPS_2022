## Program 34: Write a program to perform bubble sort
```c
#include <stdio.h>

void bubbleSort(int *arr,int len){
    int temp;
    for(int i=0;i<len;i++){
        for(int j=0;j<len-1-i;j++){
            if(arr[j+1] < arr[j]){
                //swap
                temp = arr[j];
                arr[j] = arr[j+1];
                arr[j+1] = temp;
            }
        }
    }
}

int main(){
    int len;
    printf("Enter size of array\n");
    scanf("%d",&len);
    int arr[len];
    printf("Enter elements \n");
    for(int i=0;i<len;i++){
        printf("Enter element at index %d -> ",i);
        scanf("%d",&arr[i]);
    }
    printf("\nUnsorted array is :\n");
    for(int i=0;i<len;i++){
        printf("%d\t",arr[i]);
    }
    printf("\n");
    bubbleSort(arr, len);

    printf("\nSorted array is :\n");
    for(int i=0;i<len;i++){
        printf("%d\t",arr[i]);
    }
    printf("\n");
}
```
## Output:
```
Enter size of array
10
Enter elements
Enter element at index 0 -> 55
Enter element at index 1 -> 33
Enter element at index 2 -> 22
Enter element at index 3 -> 11
Enter element at index 4 -> 77
Enter element at index 5 -> 88
Enter element at index 6 -> 66
Enter element at index 7 -> 0
Enter element at index 8 -> 99
Enter element at index 9 -> 44

Unsorted array is :
55	33	22	11	77	88	66	0	99	44	

Sorted array is :
0	11	22	33	44	55	66	77	88	99	
```
