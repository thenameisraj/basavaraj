# include<stdio.h>
void main
{
char name[50];
float unit,charge;
printf("enter the name of consumer\n");
scanf("%f",&unit);
if(unit<=200)
{
charge=unit*0.80+100;
}
else if(unit<=300)
{
charge=(200*0.80)+(unit-200)*0.90+100;
else
{
charge=(200*0.80)+(100*0.90)+(unit-300)*1+100;
}
if(charge>=400)
{
charge+=charge*0.15;
}
printf("consumer name:%s\n units consumed:%f\n rupees:%.2f\n",name,units,charge);
}
