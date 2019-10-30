# file.c
#include <stdio.h>
void swap(int ,int);
int main(void)
{
    int a=10;
    int b=45;
    
    swap(a,b);
    printf("nos swapped are a=%d and b=%d ",b,a);


    return 0;
}
void swap(int x,int y)
{
    int t=x;
    x=y;
    y=t;
}
