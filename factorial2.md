# skywalker
#include <stdio.h>

int main()
{
    int number,result = 1;
    scanf("%d", &number);
    while(number > 0)
    {
        result = result * number;
        number--;
    }
    printf("%d \n",result);
    return 0;
}
