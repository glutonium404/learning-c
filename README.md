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

2. Write a C program that accepts an employee's ID, total worked hours in a  
month and the amount he received per hour. Print the ID and salary (with two  
decimal places) of the employee for a particular month.  
Test Data :  
Input the Employees ID: 0342  
Input the working hrs: 8  
Salary amount/hr: 15000  
Expected Output:  
Employees ID = 0342  
Salary = 120000.00 BDT  

```c
#include<stdio.h>

int main() {
    double total_work_hour, amount_received;
    char id[100];

    printf("Input the Employees ID: ");
    scanf("%s", id);

    printf("Input the working hrs: ");
    scanf("%lf", &total_work_hour);

    printf("Salary amount/hr: ");
    scanf("%lf", &amount_received);

    printf("Employees ID = %s\n", id);
    printf("Salary = %.2lf BDT\n", total_work_hour * amount_received);

    return 0;
}
```

---

3. Write a C program to calculate a bike’s average consumption from the given  
total distance (integer value) traveled (in km) and spent fuel (in litters, float  
number – 2 decimal points).  
Test Data :  
Input total distance in km: 350  
Input total fuel spent in liters: 5  
Expected Output:  
Average consumption (km/lt) 70.000  

```c
#include<stdio.h>

int main() {
    int t_dis;
    double t_fuel;

    printf("Input total distance in km: ");
    scanf("%d", &t_dis);

    printf("Input total fuel in liters: ");
    scanf("%lf", &t_fuel);

    printf("Average consumption (km/lt)  %.3lf\n", t_dis/t_fuel);

    return 0;
}
```
