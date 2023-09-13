//Write a program to find the grading on basis of marks percentage using switch statement [below 30marks - failed, between 30-45 - 3rd division, between 45-75 - 2nd division, between 75-100 - first division]
#include <stdio.h>

int main() {
    float marks;
    printf("Enter your marks percentage: ");
    scanf("%f", &marks);

    int grade;

    if (marks < 0 || marks > 100) {
        printf("Invalid marks percentage!\n");
        return 1;
    }

   
    int marksInteger = (int)marks;

    
    switch (marksInteger) {
        case 0 ... 29:
            grade = 0; // Failed
            break;
        case 30 ... 44:
            grade = 3; // 3rd division
            break;
        case 45 ... 74:
            grade = 2; // 2nd division
            break;
        case 75 ... 100:
            grade = 1; // 1st division
            break;
        default:
            printf("Invalid marks percentage!\n");
            return 1;
    }

    // Display the grade
    switch (grade) {
        case 0:
            printf("You have failed.\n");
            break;
        case 1:
            printf("You are in the 1st division.\n");
            break;
        case 2:
            printf("You are in the 2nd division.\n");
            break;
        case 3:
            printf("You are in the 3rd division.\n");
            break;
        default:
            printf("Invalid grade.\n");
            break;
    }

    return 0;
}
