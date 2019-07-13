# skywalker
#include <stdio.h>
int main()
{
    int n[5],s=0,i;
    for(i=0;i<5;i++)
    {
    printf("Input ");
    scanf("%d" ,&n[i]);
    s+=n[i];
    }
    s=s/5;
    printf("%d",s);
    return 0;
}
