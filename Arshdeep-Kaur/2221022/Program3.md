## Program 3: Write a program to input two numbers using scanf() and add them

#include <stdio.h>

int main()

{    

    int a, b, sum;
    
    printf("Enter two numbers: ");
    
    scanf("%d %d", &a, &b);

    // calculating sum
    sum = a + b;      
    
    printf("%d + %d = %d", a, b, sum);
    
    return 0;
    
}

**Output* : Enter two numbers: 5

**20

**5 + 20 = 25
