
## Taking a look at the first C program

```c
/*
    comments
*/
#include<stdio.h> // preprocessor commands

int main() {
    int a; // local declaration
    printf("Hello World"); // function call
    return 0; // return statement
}

// function definition
int sum(int a, int b) {
    return a + b;
}

```

- What are comments?
  - These are the code-pieces that are completely ignored by the compiler
  - They are just used by the programmer to add some help-text in code
  - Types of comments:
    - Single line comments
    - Multi line commnets
- Preprocessing commands
  - It is optional
  - Used to include header files and to define constants
- Global declarations
  - Global (will be accessible across functions)
- Functions
  - return statements
