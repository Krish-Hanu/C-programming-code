#include<stdio.h>
int main() {
float a,b,c,d;
int x;
printf("Enter price of product a:",a);
scanf("%f",&a);
printf("Enter price of product b:",b);
scanf("%f",&b);
printf("Enter price of product c:",c);
scanf("%f",&c);
printf("Enter price of product d:",d);
scanf("%f",&d);
x=(int)a+(int)b+(int)c+(int)d;
printf("------TOTAL PRICE-------"\n);
printf("You have to pay only %d rupees");
return 0;
}
