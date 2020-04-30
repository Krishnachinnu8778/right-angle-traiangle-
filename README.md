#include<stdio.h>
int main()
{
  int a= 01;
  int i,j;
  for(i=1;i<=5;i++)
  {
    for(j=1;j<=i;j++)
    {
    printf("%d", &a );
  }  
   printf("\n");
   }
   return 0;
}

