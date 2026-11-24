# Functions in C — Library Functions and Your Own

## Do it first

You have called functions since the first program — printf did your printing. This lesson turns the caller into an author: C's programs are built of functions, the library lends hundreds, and the rest you write. The chapter's programs stop being lists and become organisations here.

## Sub lesson 1 — Library functions — the borrowed toolbox

**Library functions** are ready-made functions the language provides: **sqrt** for square roots, **pow** for powers, the string functions of the companion lesson, printf and scanf themselves. They are reached through **headers** — `#include <math.h>` borrows the mathematics toolbox as `<stdio.h>` borrowed input-output. Calling is one pattern everywhere: the function's **name**, the **arguments** in brackets, and the **returned value** used where the call stands: `area = sqrt(x);` — the call is replaced by its answer.

In your mind's eye: library functions — the borrowed toolbox.

## Sub lesson 2 — Your own functions — prototype, definition, call

A **user-defined function** is written in three parts. The **prototype** — `int add(int, int);` — declares the function's name, what it takes and what it returns, so the compiler can check every call. The **definition** holds the body: the work, ending in **return**. The **call** uses it from main or anywhere, as often as needed — write once, use everywhere, fix in one place. Functions divide a program the way chapters divide a book: by their jobs — and the good-structure lesson's readability is mostly this division, done well.

In your mind's eye: your own functions — prototype, definition, call.

## Say it to your companion

Tell your companion, in your own words: **Library functions** are ready-made functions the language provides: **sqrt** for square roots, **pow** for powers, the string functions of the companion lesson, printf and scanf themselves. They are reached through **headers** — `#include <math.h>` borrows the mathematics toolbox as `<stdio.h>` borrowed input-output. Calling is one pattern everywhere: the function's **name**, the **arguments** in brackets, and the **returned value** used where the call stands: `area = sqrt(x);` — the call is replaced by its answer. A **user-defined function** is written in three parts. The **prototype** — `int add(int, int);` — declares the function's name, what it takes and what it returns, so the compiler can check every call. The **definition** holds the body: the work, ending in **return**. The **call** uses it from main or anywhere, as often as needed — write once, use everywhere, fix in one place. Functions divide a program the way chapters divide a book: by their jobs — and the good-structure lesson's readability is mostly this division, done well. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: sqrt and pow (also printf, scanf). Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: <math.h>. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The name, the arguments, and the returned value used. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Its answer — the returned value. Do this with a real example of your own and write or say how you know it is right.
