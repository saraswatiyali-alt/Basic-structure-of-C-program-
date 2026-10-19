# Basic-structure-of-C-program-
The basic structure of a C program consists of different sections that help us write, compile, and execute a program in an organized way.
1. Structure of a C Program
   
#include <stdio.h>       // Documentation/Link section

int main()               // Main function
{
    printf("Hello World");  // Executable statement

    return 0;            // Return statement
}


2. Different Sections of a C Program
1. Documentation Section
- Contains comments that describe the program.
- Comments help programmers understand the code.
- Example: // Program to print Hello World
2. Link Section
- Includes the required header files in the program.
- The #include directive is used to include header files.
- Example: #include <stdio.h>
3. Definition Section
- Defines symbolic constants using the #define directive.
- Example: #define PI 3.14
4. Global Declaration Section
- Declares global variables and function prototypes.
- These declarations can be used by multiple functions in the program.
5. Main Function Section
- The main() function is the starting point of program execution.
- Every standard hosted C program must have a main() function.
6. Declaration Section
- Declares local variables used inside a function.
- Example: int a, b;
7. Executable Section
- Contains statements that perform operations.
- Example: printf("Hello World");
8. Return Statement

- The return 0; statement indicates successful termination of the program.
