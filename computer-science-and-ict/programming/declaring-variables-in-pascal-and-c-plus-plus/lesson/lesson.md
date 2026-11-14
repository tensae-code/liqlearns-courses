# Declaring Variables in Pascal and C++

## Do it first

Data enters a program through declarations: the act that brings a variable into existence with a name and a type. The pair's two placements of that act — all up front, or where needed — is a real design difference.

## Sub lesson 1 — Pascal's var section — all names before the work

In Pascal, variables are declared in the **var section** between the heading and begin: `var a, b: integer; x: real;` — several names may share one type in one line. The declaration **reserves memory, fixes the type, and introduces the name** for the whole block; a variable not declared does not exist for the compiler, and using one is the beginner's first error message. Declaration is not assignment: a fresh variable's value is **undefined** until the program gives it one.

[Picture — Pascal's var section — all names before the work]

## Sub lesson 2 — C++'s declarations — where needed, with initial values

C++ allows a declaration **wherever an instruction may stand**, and lets it carry an **initial value**: `int a = 5;` declares and assigns in one breath — and a for loop may declare its own steer in its heading: `for (int i = 0; …)`. The freedom has a shadow discipline: a name exists only **from its declaration to the end of its block** — C++'s first sight of the scope Grade 12 formalises. Pascal's gathered var section trades that freedom for a single census of a block's data, read at a glance.

[Picture — C++'s declarations — where needed, with initial values]

## Say it to your companion

Tell your companion, in your own words: In Pascal, variables are declared in the **var section** between the heading and begin: `var a, b: integer; x: real;` — several names may share one type in one line. The declaration **reserves memory, fixes the type, and introduces the name** for the whole block; a variable not declared does not exist for the compiler, and using one is the beginner's first error message. Declaration is not assignment: a fresh variable's value is **undefined** until the program gives it one. C++ allows a declaration **wherever an instruction may stand**, and lets it carry an **initial value**: `int a = 5;` declares and assigns in one breath — and a for loop may declare its own steer in its heading: `for (int i = 0; …)`. The freedom has a shadow discipline: a name exists only **from its declaration to the end of its block** — C++'s first sight of the scope Grade 12 formalises. Pascal's gathered var section trades that freedom for a single census of a block's data, read at a glance. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: In the var section, between the heading and begin. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Yes — var a, b: integer;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Reserves memory, fixes the type, introduces the name. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Undefined — until the program assigns one. Do this with a real example of your own and write or say how you know it is right.
