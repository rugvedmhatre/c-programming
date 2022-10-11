#Introduction to C Programming 
---

### Table of Contents

1. [Hello World](#helloworld)

<h2 id="helloworld">Hello World</h2>

As per programming traditions, our first program will be to print out "hello world" in the Terminal

Code : [01\_helloworld.c](https://github.com/rugvedmhatre/c-programming/blob/main/01_hello_world.c)

- Header Files
  
  We start by importing standard input/output header file. This includes the functions we require to print out on the screen. [Learn more](https://gcc.gnu.org/onlinedocs/cpp/Header-Files.html#:~:text=A%20header%20file%20is%20a,preprocessing%20directive%20'%20%23include%20'.)
  
  ```
  #include <stdio.h>
  ```
  

- Function
  - The ['main'](https://learn.microsoft.com/en-us/cpp/c-language/main-function-and-program-execution?view=msvc-170) function is a primary function in C code, it is the starting point for execution.
  - The function has various [return types](https://learn.microsoft.com/en-us/cpp/c-language/return-statement-c?view=msvc-170): void, int, float and more. In case, we return a wrong type we get a compilation error.
  - If we have to mention [arguments](https://learn.microsoft.com/en-us/cpp/c-language/arguments?view=msvc-170) to the function, we add them in the parenthesis '( )' after the function name. 
    (In our program, currently no paramters are required)
  - The statements inside the function are enclosed in curly brackets '{ }'
  - Since our function is an 'int' type, we need to return some integer at the end of function.
  - We are returning 0 
    (Returning 0 indicates successful execution)

- Statements (printf)
  - We use [printf function](https://cplusplus.com/reference/cstdio/printf/) to print out characters on the Terminal
  - We are passing the string enclosed in quotes " " as an argument to the printf function.
  - We end each statement in C with a semi-colon ';'

**Compiling the program**

- C Programs need to be compiled first, to get an executable file.
- These compilations are handled by a compiler like [gcc](https://gcc.gnu.org/).
- To install gcc on Windows, watch [this](https://youtu.be/lqzuR2USKRM)
- It is preinstalled on Mac and Linux.

To compile the program on a Mac, we run the following command:

```
gcc 01_helloworld.c -o 01_helloworld.out
```

And to run the executable we run 01\_helloworld.out in Terminal:

```
./01_helloworld.out
```

We should get the output like:

```
Hello World
```