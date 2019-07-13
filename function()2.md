# skywalker
#include <stdio.h>
int function(int a);
{
    if(a<0)
    {
    a=0-a;
    return a;
    }
    else
    {
    a=a;
    }
    
}

void main()
{
    int sum,a;
    printf("Input : ");
    scanf("%d",a);
    sum=function(a);
    printf("%d",sum);
}
