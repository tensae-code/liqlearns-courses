# Compiler Directives in Pascal and C++

## Do it first

A program talks to two audiences: the machine that will run it, and the compiler that must first build it. Grade 10's vocabulary chapter closes with the messages meant for the second audience.

## Sub lesson 1 — Directives — orders to the builder

A **compiler directive** is an instruction **to the compiler, not to the program**: it changes how the program is built, and itself executes nothing at run time. Pascal writes directives as special comments — **{$R+}** switches range checking on, {$R−} off; others govern overflow checks, input/output checks, debug information. The directive's home is the exact place it stands: a switch rules the text after it until switched again. Removing all directives changes no algorithm — it changes the **safety and shape of the building**.

In your mind's eye: directives — orders to the builder.

## Sub lesson 2 — C++'s preprocessor — directives before the compiler

C++ gives this work to a **preprocessor** that runs **before** compilation, driven by lines beginning with **#**: **#include** inserts a whole file's text (the libraries' headers), **#define** names a text substitution used through the program, **#ifdef / #endif** include or exclude whole parts of the text by condition. The famous first line of every C++ program, `#include <iostream>`, is a directive — the program's first word is spoken not to the machine, but to the builder about where its tools live.

In your mind's eye: c++'s preprocessor — directives before the compiler.

## Say it to your companion

Tell your companion, in your own words: A **compiler directive** is an instruction **to the compiler, not to the program**: it changes how the program is built, and itself executes nothing at run time. Pascal writes directives as special comments — **{$R+}** switches range checking on, {$R−} off; others govern overflow checks, input/output checks, debug information. The directive's home is the exact place it stands: a switch rules the text after it until switched again. Removing all directives changes no algorithm — it changes the **safety and shape of the building**. C++ gives this work to a **preprocessor** that runs **before** compilation, driven by lines beginning with **#**: **#include** inserts a whole file's text (the libraries' headers), **#define** names a text substitution used through the program, **#ifdef / #endif** include or exclude whole parts of the text by condition. The famous first line of every C++ program, `#include <iostream>`, is a directive — the program's first word is spoken not to the machine, but to the builder about where its tools live. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An instruction to the compiler — changing how the program is built, executing nothing at run time. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: As special comments — {$R+} and its kin. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Range checking. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The text after it, until switched again. Do this with a real example of your own and write or say how you know it is right.
