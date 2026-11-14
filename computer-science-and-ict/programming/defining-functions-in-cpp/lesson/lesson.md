# Defining Functions in C++

## Do it first

When the same job appears three times in a program, it should be written once. This lesson writes that once — a function of your own.

## Sub lesson 1 — The shape of a definition

A **function definition** has four parts: the **return type** (what kind of value it gives back, or **void** for none), the **name**, the **parameters** in round brackets (the inputs it accepts, each with its type), and the **body** in braces — the statements that do the work, ending with **return** when a value goes back. Until it is **called**, a defined function does nothing at all.

[Picture — the shape of a definition]

## Sub lesson 2 — Calling and reusing

A **call** writes the function's name with **arguments** — real values for the parameters — and the program jumps into the body, runs it, and **returns to the exact place of the call**, carrying the returned value if there is one. One definition then serves every call site: fix the body once and every call is fixed. main() itself is a function — the one the system calls first.

[Picture — calling and reusing]

## Say it to your companion

Tell your companion, in your own words: A function in C++ is a named block of code written once and called whenever needed: its definition gives the return type, the name, the parameter list in brackets and the body in braces, and a call runs the body and hands control back to the place that called it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Return type, name, parameters and body. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In round brackets after the name. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The real values given for the parameters at a call. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: One fix in the body fixes every call. Do this with a real example of your own and write or say how you know it is right.
