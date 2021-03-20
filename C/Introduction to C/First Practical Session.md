
### Hello world program
```C
#include<stdio.h>

int main() {
    printf("Hello world");
    return 0;
}
```

----

### Printing an integer
```c 
#include<stdio.h>

int main() {
    int a = 4;
    printf("Hello world - %d", a);
    return 0;
}
```

----


### sum of 2 numbers
```C
#include<stdio.h>

int main() {
    int a = 4;
    int b = 5;
    int sum = a + b;
    printf("sum = %d", sum);
    return 0;
}
```

----


### product of 2 mumbers

```C
#include<stdio.h>

int main() {
    int a = 4;
    int b = 5;
    int product = a * b;
    printf("Product = %d", product);
    return 0;
}
```

----


### basic if statement

```C
#include<stdio.h>

int main() {
    int a = 0; // declaration + initialization
    if (4 <= 2) {
        a = 5;
    }
    printf("value of a = %d", a);
}
```

----



### basic if else statement
```C
#include<stdio.h>

int main() {
    int a = 0; // declaration + initialization
    if (4 <= 2) {
        a = 5;
    } else {
        a = 9;
    }
    printf("value of a = %d", a);
}
```


----


### basic for loop
```C
#include<stdio.h>

int main() {
    int i; // declaration
    for (i=1; i<=10; i++) {
        printf("Hello World\n");
    }
    return 0;
}
```


----


### printing number from 1 to 10
```C
#include<stdio.h>

int main() {
    int i; // declaration
    for (i=1; i<=10; i++) {
        printf("%d\n", i);
    }
    return 0;
}
```

----


### printing numbers from 10 to 1 in reverse order
```C
#include<stdio.h>

int main() {
    int i; // declaration
    for (i=10; i>=1; i--) {
        printf("%d\n", i);
    }
    return 0;
}
```


----


### basic arrays
```C
#include<stdio.h>

/*
    This is a multi-line comment
    this is the second line of the comment
*/

int main() {
    int a[5]; // declaration of array
    a[0] = 10; // initialization of first element of the array
    a[1] = 20; // initialization of second element of the array
    a[2] = 30;
    a[3] = 40;
    a[4] = 50;

    printf("%d\n", a[2]); // accessing the third elemnt

    return 0;
}
```


----


### sum of elements in array without loop
```C
#include<stdio.h>

/*
    This is a multi-line comment
    this is the second line of the comment
*/

int main() {
    int a[5]; // declaration of array
    int sum;
    a[0] = 10; // initialization of first element of the array
    a[1] = 20; // initialization of second element of the array
    a[2] = 30;
    a[3] = 40;
    a[4] = 50;

    sum = a[0] + a[1] + a[2] + a[3] + a[4];

    printf("sum = %d\n", sum); // accessing the third elemnt

    return 0;
}
```

----


### sum of elements of an array using loop
```C
#include<stdio.h>

/*
    This is a multi-line comment
    this is the second line of the comment
*/

int main() {
    int a[5]; // declaration of array
    int sum, i;
    a[0] = 10; // initialization of first element of the array
    a[1] = 20; // initialization of second element of the array
    a[2] = 30;
    a[3] = 40;
    a[4] = 50;

    sum = 0;
    for (i=0; i<5; i++) {
        sum = sum + a[i];
    }

    printf("sum = %d\n", sum); // accessing the third elemnt

    return 0;
}
```

----


### swapping 2 numbers
```C
#include<stdio.h>

int main() {
    int a = 5;
    int b = 6;
    int temp;
    printf("values before swapping: ");
    printf("a=%d, b=%d\n", a, b);

    // we'll swap here
    temp = a;
    a = b;
    b = temp;

    printf("values after swapping: ");
    printf("a=%d, b=%d\n", a, b);
    return 0;
}
```


----


### modulus operator
```c 
#include<stdio.h>

int main() {
    int a = (17 % 3);
    int b = 23 % 4; // modulus operator
    printf("value of a is: %d\n", a);
    printf("value of b is: %d\n", b);

    return 0;
}
```

----


### checking even and ood numbers using if
```c
#include<stdio.h>

int main() {
    int a = 20;
    
    if (a%2 == 0) {
        printf("this number is even");
    } else  {
        printf("this number is odd");
    }

    return 0;
}
```

----


### printing odd numbers from 1 to 20
```c
#include<stdio.h>

int main() {
    int i;

    for (i=1; i<=20; i++) {
        if (i%2 == 1) {
            printf("%d\n", i);
        }
    }

    return 0;
}
```

----


### if-else inside for loop
```c
#include<stdio.h>

int main() {
    int i;

    for (i=1; i<=20; i++) {
        if (i%2 == 1) {
            printf("%d - odd\n", i);
        } else {
            printf("%d - even\n", i);
        }
    }

    return 0;
}
```

----


### printing even numbers from 1 to 20
```c
#include<stdio.h>

int main() {
    int i;

    for (i=1; i<=20; i++) {
        if (i%2 == 0) {
            printf ("%d\n", i);
        }
    }

    return 0;
}
```

----


### simple for loop
```c
#include<stdio.h>

int main() {
    int i;
    for (i=0; i<5; i++) {
        printf("Hello\n");
        printf("Hi\n");
    }
    return 0;
}
```


----


### nested for loop
```c
#include<stdio.h>

int main() {
    int i, j;
    for (i=0; i<6; i++) { // for rows
        for (j=0; j<10; j++) { // for columns
            printf("*");
        }
        printf("\n");
    }

    return 0;
}
```

----

