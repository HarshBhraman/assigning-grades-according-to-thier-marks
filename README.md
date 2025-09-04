/*Write a program to assign grades based on marks:
	90–100 ? A
	75–89 ? B
	50–74 ? C
	< 50 ? Fail		*/

#include <stdio.h>

int main() {
    int marks;

    printf("Enter your marks: ");
    scanf("%d", &marks);

    if (marks >= 90 && marks <= 100) {
        printf("Grade: A\n");
    } else if (marks >= 75 && marks <= 89) {
        printf("Grade: B\n");
    } else if (marks >= 50 && marks <= 74) {
        printf("Grade: C\n");
    } else if (marks >= 0 && marks < 50) {
        printf("Grade: Fail\n");
    } else {
        printf("Invalid input. Marks should be between 0 and 100.\n");
    }

    return 0;
}
