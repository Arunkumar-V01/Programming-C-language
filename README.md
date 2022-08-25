# swapping-of-two-numbers
#include <stdio.h>

int main()
{
    int a,b;
    a=7;
    b=3;
    printf("before swapping the value of a is %d the value of b is %d", a, b);
a=a+b;
b=a-b;
a=a-b;
    
printf("\nafter swapping the value of a is%d the value of b is %d", a, b);

    return 0;
}
