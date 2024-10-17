
#include<stdio.h>
int main()
{
char operator;
int a,b,result;
char choice;
do
{
printf(": ");
scanf("%d",&a);
printf(": ");
scanf("%c",&operator);
printf(": ");
scanf("%d",&b);

switch (operator)

{
case'+':
 result= a+b;
 break;
 case'-':
 result= a-b;
 break;
 case'*':
 result= a*b;
 break;
 case'/':
 if(b!=0)
 {
 result= a/b;
 }
 else
 printf("error ");
 break;
 default:
 printf(" error in operation");
 }
 printf("%d\n",result);
 printf("powered by yogendra meena\n");
 printf("do you want perform another operation(y,n): ");
 getchar();
 scanf("%c",&choice);
 }
 while (choice=='y' || choice=='Y');
 return 0;
 }
    
