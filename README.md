#include<stdio.h>
struct employee{
char name[30];
int emId;
float salary;
};
int main()
{
struct employee emp;
printf("\n Enter details:");
printf("Name?:");   gets(emp.name);
printf("ID?:");     scanf("%d",&emp.empID);
printf("Salary?:");  
scanf("%f",&emp.salary);
printf("\nEnter details:");
printf("Name:%s",emp.name);
printf("ID:%d",emp.empID);
printf("Salary:%f",emp.salary);
return 0;
}

