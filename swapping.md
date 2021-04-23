# tom-and-jerrry
#include<stdio.h>
#include<conio.h>
void main()
{
  int x,y;
  clrscr();
  printf("enter any two values");
  scanf("%d %d",&x,&y);
  x=x+y;
  y=x-y;
  x=x-y;
  printf("after interchange:");
  printf("\n value of x %d & y=%d",x,y);
  getch();
}  
  
