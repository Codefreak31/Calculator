# Calculator
#include<stdio.h>
#include<conio.h>
int main()
{
int a = 30;
int b = 15;
int c;
int d;
int e;
int f;

c = a +b;
d = a - b;
e = a * b;
f = a / b;

printf("The sum of %d and %d is %d\n", a, b, c);
printf("The difference of %d and %d is %d\n", a, b, d);
printf("The product of %d and %d is %d\n", a, b, e);
printf("The divison of %d and %d is %d\n", a, b, f);
getch();
return 0;
}
