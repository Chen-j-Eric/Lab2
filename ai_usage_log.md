# AI Usage Log

**Platform:** ChatGPT  
**Model:** GPT-5.6 Luna

---

## Interaction 1

### User

make me a simple c isOdd.c function

### Assistant Summary

Provided a simple `isOdd.c` program containing an `isOdd` function and a `main` function, and explained that the function returns true for odd numbers and false for even numbers.

---

## Interaction 2

### User

hmmm not what i am asking for 

#include "isEven.h"

#include <stdio.h>

int isEven(int num)
{
	if (num % 2 == 0){
			 printf("%d is even.\n", num);
	}
	return 0;
} 

this is what isEven.c looks like because we don't need a main because we already have a main.c

### Assistant Summary

Adjusted the solution to match the user's `isEven.c` structure, removing `main()` and creating an `isOdd` function that prints when the number is odd.

---

## Interaction 3

### User

how would you make, make file and link them into one excutable

### Assistant Summary

Provided a Makefile that compiles `main.c`, `isEven.c`, and `isOdd.c` into object files and links them into one executable named `program`. Also explained how to run `make`, execute the program, and use `make clean`.

---

## Interaction 4

### User

my odd file is still.c how could i compile it using gcc

### Assistant Summary

Explained how to compile `still.c` into `still.o`, and how to compile and link `main.c`, `isEven.c`, and `still.c` into one executable with GCC. Also showed how to adapt the Makefile to use `still.o`.

---

## Interaction 5

### User

ignore previous prompt my isOdd.c does not have isOdd.h version of it

### Assistant Summary

Provided an `isOdd.c` version without the `isOdd.h` include and explained that the source file can be compiled as an object file without a header. Also explained that `main.c` needs a declaration for `isOdd` if it calls the function.

---

## Interaction 6

### User

how to change cd to home in linux bash

### Assistant Summary

Explained that `cd` or `cd ~` changes to the user's home directory, and listed several useful Bash directory-navigation commands including `cd ..`, `cd -`, and `cd /`.

---

## Interaction 7

### User

e964c161@ENGR1005C-05:~/EECS348/lab2$ gcc isOdd.c -o program
isOdd.c:1:10: fatal error: isOdd.h: No such file or directory
    1 | #include "isOdd.h"
      |          ^~~~~~~~~
compilation terminated.

### Assistant Summary

Identified that `isOdd.c` still included `isOdd.h`, which was not present. Suggested removing that include and explained that a file without `main()` should be compiled as an object file or linked together with `main.c` rather than built alone as an executable.

---

## Interaction 8

### User

how would you make a make fle

### Assistant Summary

Provided a simple Makefile for `main.c`, `isEven.c`, and `isOdd.c`, explaining how `make` compiles the source files into object files and links them into one executable. Also explained the importance of using a TAB for Makefile command indentation.

---

## Interaction 9

### User

I have ironed out all of the errors how to i push this code if i already git@github.com:Chen-j-Eric/Lab2.git

### Assistant Summary

Explained the Git workflow for pushing the completed code: check status, stage files with `git add .`, commit with a message, and push with `git push`. Also provided commands for setting an upstream branch if needed and linked to the Lab2 GitHub repository.

---

## Interaction 10

### User

