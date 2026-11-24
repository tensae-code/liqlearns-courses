# The Structure of a Pascal and C++ Program

## Do it first

Grade 10's theory closes by assembling everything into one map: the whole structure of a program, in the two languages, part by part. If you can read this map, you can open any program in the course and know where you are.

## Sub lesson 1 — Pascal's anatomy — front matter, then the body

A Pascal program stands in fixed order: the **heading** (`program Name;`), then the **declaration part** — label, const, type, var sections, and the **subprogram declarations** (procedures and functions, each a small program in shape) — then the **main body** between begin and end. Nothing may appear out of its place: the compiler reads the program as it is built, declarations before use, always. The structure is the discipline made visible — the program as a document with a constitution and then its acts.

In your mind's eye: pascal's anatomy — front matter, then the body.

## Sub lesson 2 — C++'s anatomy — includes, functions, main

A C++ program is a **set of functions** with no fixed gathering: **preprocessor directives** (#include for the libraries) come first; **global declarations** and **function definitions** follow in any order the compiler can resolve; and **main** is the function where execution begins — one function among the set, marked by its name. Where Pascal is one document in fixed order, C++ is a **workshop of named tools** with main as the door. Both anatomies serve the same law: **everything used is declared, and execution starts at a known place**.

In your mind's eye: c++'s anatomy — includes, functions, main.

## Say it to your companion

Tell your companion, in your own words: A Pascal program stands in fixed order: the **heading** (`program Name;`), then the **declaration part** — label, const, type, var sections, and the **subprogram declarations** (procedures and functions, each a small program in shape) — then the **main body** between begin and end. Nothing may appear out of its place: the compiler reads the program as it is built, declarations before use, always. The structure is the discipline made visible — the program as a document with a constitution and then its acts. A C++ program is a **set of functions** with no fixed gathering: **preprocessor directives** (#include for the libraries) come first; **global declarations** and **function definitions** follow in any order the compiler can resolve; and **main** is the function where execution begins — one function among the set, marked by its name. Where Pascal is one document in fixed order, C++ is a **workshop of named tools** with main as the door. Both anatomies serve the same law: **everything used is declared, and execution starts at a known place**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The heading — program Name;. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: label, const, type and var — then the subprogram declarations. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The instructions between begin and the final end.. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — declarations stand before use, always. Do this with a real example of your own and write or say how you know it is right.
