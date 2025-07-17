```c
#include <stdio.h>

int main() {
    for(int i=0; i<10; i++) {
        printf("Tahzib ");
    }
}
```

```c
#include <stdio.h>

int main() {
    printf("Number from 0 to 10:\n");

    for(int i=0; i<=10; i++) {
        printf("%d ", i);
    }

    printf("\n\nNumber from 10 to 0:\n");

    for(int i=10; i>=0; i--) {
        printf("%d ", i);
    }

    printf("\n");
}
```

```c
#include <stdio.h>

int main() {
    int sum = 0;

    printf("The first 10 natural numbers are:\n");

    for(int i=1; i<=10; i++) {
        printf("%d ", i);
        sum += i;
    }

    printf("\nThe Sum is: %d ", sum);
}
```

```c
#include <stdio.h>

int main() {
    int sum = 0;
    printf("Input the 10 numbers:\n");
    for(int i=1; i<=10; i++) {
        int n;
        printf("Number-%d :", i);
        scanf("%d", &n);
        sum += n;
    }
    printf("The sum of 10 no is: %d\n", sum);
    printf("The Avarage is: %lf\n", sum/10.0);
}
```

```c
#include <stdio.h>

int main() {
    int terms = 0;
    printf("Input number of terms: ");
    scanf("%d", &terms);
    for(int i=1; i<=terms; i++) {
        printf("Number is : %d and cube of the %d is :%d\n", i, i, i*i*i);
    }
}
```

```c
#include <stdio.h>

int main() {
    int n = 0;
    printf("Input the number (Table to be calculated): ");
    scanf("%d", &n);
    for(int i=1; i<=10; i++) {
        printf("%d * %d = %d\n", n, i, i*n);
    }
}
```

```c
#include <stdio.h>

int main() {
    int n = 0, sum = 0;
    printf("Input number of terms: ");
    scanf("%d", &n);
    printf("The odd numbers are:");
    for(int i=1, c=1; i<=n; i++) {
        printf("%d ", c);
        sum += c;
        c += 2;
    }
    printf("\nThe Sum of odd Natural Numbers up to %d terms: %d\n", n, sum);
}
```
