# skywalker
#include <stdio.h>

void update(int *y){
  *y = 8;
}


int main(){
  int a = 5;

  int *pa = &a;

  printf("Before: Pointer value %d\n",*pa);

  update(pa);

  printf("After: Pointer value %d\n", *pa);


  printf("A Value %d\n", a);

return 0;

}
