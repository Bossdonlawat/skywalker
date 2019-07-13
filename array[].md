# skywalker
#include <stdio.h>
int main(){
    int a[10] = {3,4,5,6,7,8,8,9,0,2};
    int i=0,s=0;
    for(i; i<10; i++)
    {
        s+=a[i]; // s=s+a[ตัวที่] 
    }
    printf(" %d \n",s);
    return 0;
}
