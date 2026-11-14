# A First C Program — Hello World and the main Function

## Do it first

Every programming language has a first program, and by tradition it prints one greeting: Hello World. In C the greeting wears the language's whole skeleton — headers above, main in the middle, statements inside braces. Learn the skeleton once and every C program you ever meet is already half read.

## Sub lesson 1 — The skeleton — headers and main

A C program begins with **header lines** — `#include <stdio.h>` borrows the standard input-output library, the toolbox holding printf and scanf. Below it stands the **main() function**: `int main()` — the function the machine **starts at**, every time; a C program may hold many functions, but execution begins at main or nowhere. The function's body lives between **braces { }**, and each statement inside ends with a **semicolon** — C's full stop.

[Picture — The skeleton — headers and main]

## Sub lesson 2 — Hello World — and running it in Code::Blocks

The first program's whole work is one statement: `printf("Hello World");` — print the words between the quotes to the screen. The book writes and runs it in **Code::Blocks**, the free development environment of the HSC course: create the project, type the program exactly, **build** (the compiler translates it — the translator lesson at work), **run**, and read the greeting in the console window. When the greeting fails to appear, the compiler's error list is the first debugging text a C programmer learns to read: it names the line, and the fault is almost always a missing semicolon or brace — the skeleton's small bones, already teaching their importance.

[Picture — Hello World — and running it in Code::Blocks]

## Say it to your companion

Tell your companion, in your own words: A C program begins with **header lines** — `#include <stdio.h>` borrows the standard input-output library, the toolbox holding printf and scanf. Below it stands the **main() function**: `int main()` — the function the machine **starts at**, every time; a C program may hold many functions, but execution begins at main or nowhere. The function's body lives between **braces { }**, and each statement inside ends with a **semicolon** — C's full stop. The first program's whole work is one statement: `printf("Hello World");` — print the words between the quotes to the screen. The book writes and runs it in **Code::Blocks**, the free development environment of the HSC course: create the project, type the program exactly, **build** (the compiler translates it — the translator lesson at work), **run**, and read the greeting in the console window. When the greeting fails to appear, the compiler's error list is the first debugging text a C programmer learns to read: it names the line, and the fault is almost always a missing semicolon or brace — the skeleton's small bones, already teaching their importance. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The standard input-output library. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: printf and scanf. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: At the main() function. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Braces { }. Do this with a real example of your own and write or say how you know it is right.
