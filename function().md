# skywalker
#include <stdio.h>
int max(int a,int b)
{
    int result;
    result=a*b;
    return result;

}

void main()
    {
        int sum,x,y;
        printf("Input : ");
        scanf("%d %d",&x,&y);
        sum=max(x,y);
        printf("Result %d \n",sum);
    }
