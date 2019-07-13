# skywalker
#include <stdio.h>
int main()
{
    int x;
    char c='*';
    printf("");
    scanf("%d",&x);

    for(int y=0;y<x;y++)
    {
        for(int j=0;j<=y;j++)
        {
        printf("%c ",c);
        }
        printf("\n");
    }
    return 0;
}
