# check-data
#include <stdio.h>
 
/*structure declaration*/
struct employee{
    char    name[30];
    int     age;
    float   salary;
    long  phoneno;
    char departname[100];
};
 
int main()
{
    /*declare structure variable*/
    struct employee emp;
     
    /*read employee details*/
    printf("\nEnter details :\n");
    printf("Name ?:");          gets(emp.name);
    printf("AGE ?:");            scanf("%d",&emp.age);
    printf("Salary ?:");        scanf("%f",&emp.salary);
    printf("PHONE NO:");        scanf("%ld",&emp.phoneno);
    printf("DEPARTMENT NAME:"); gets(emp.departname);
     
    /*print employee details*/
    printf("\nEntered detail is:");
    printf("Name: %s"   ,emp.name);
    printf("AGE: %d"     ,emp.empId);
    printf("Salary: %f\n",emp.salary);
    printf("PHONE No:%ld",emp.phoneno);
    printf("DEPARTMENT NAME: %s",emp.departname);
    return 0;
}
