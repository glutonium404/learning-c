1. Write a C program that accepts two courses' grades and credit hours of those
courses (floating point values) and calculates your CGPA.
Test Data :
Grade in course-1: 3.75
Credit hour of course-1: 3
Grade in course-2: 3.50
Credit hour of course-2: 1.5
Expected Output:
CGPA = 3.66

```c
#include<stdio.h>

int main() {
    double g1, c1, g2, c2;

    printf("Grade in course-1: ");
    scanf("%lf", &g1);
    printf("Credit hour of course-1: ");
    scanf("%lf", &c1);
    printf("Grade in course-2: ");
    scanf("%lf", &g2);
    printf("cCredit hour of course-2: ");
    scanf("%lf", &c2);

    double cg = (g1 * c1 + g2 * c2) / (c1 + c2);

    printf("CGPA = %.2lf\n", cg);
}
```

---
