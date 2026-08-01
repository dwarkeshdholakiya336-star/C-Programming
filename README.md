# C-Programming
#include <stdio.h>

int main()
{
    char studentName[50];
    int rollNumber;
    int age;
    char branch[50];
    int semester;
    float percentage;
    char grade;

    printf("=========================================\n");
    printf("      STUDENT MANAGEMENT SYSTEM\n");
    printf("=========================================\n\n");

    printf("Enter Student Name : ");
    scanf("%s", studentName);

    printf("Enter Roll Number : ");
    scanf("%d", &rollNumber);

    printf("Enter Age : ");
    scanf("%d", &age);

    printf("Enter Branch : ");
    scanf("%s", branch);

    printf("Enter Semester : ");
    scanf("%d", &semester);

    printf("Enter Percentage : ");
    scanf("%f", &percentage);

    printf("Enter Grade : ");
    scanf(" %c", grade);

    printf("\n=========================================\n");
    printf("          STUDENT REPORT\n");
    printf("=========================================\n");

    printf("Student Name : %s\n", studentName);
    printf("Roll Number  : %d\n", rollNumber);
    printf("Age          : %d\n", age);
    printf("Branch       : %s\n", branch);
    printf("Semester     : %d\n", semester);
    printf("Percentage   : %.1f%%\n", percentage);
    printf("Grade        : %c\n", grade);

    printf("=========================================\n");
    printf("            THANK YOU\n");
    printf("=========================================\n");

    return 0;
}
