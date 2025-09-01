# input-an-integer-and-a-float-and-print-their-sum.

#include <stdio.h>
#define pi 3.14
int main()
{
  int x;
  float y;
  float sum;
  

  printf("enter x\n:");
  scanf("%d", &x);
  
  printf("enter y\n:");
  scanf("%f", &y);
  
  sum=x+y;
  
  printf("sum %d %f", sum);
  
}
