# C Data Types — char, int, float and double

## Do it first

Before a C variable can hold anything, C demands to know what kind of thing it will hold — a letter, a count, a measurement — because the type decides the memory it gets and the arithmetic it obeys. Choosing types is the programmer's first act of honesty about their data.

## Sub lesson 1 — char and int — characters and whole numbers

The **char** type holds **one character** — one byte — stored as its code number (the character-codes lesson): 'A' is kept as 65. The **int** type holds **whole numbers** — counts, ages, marks — in (commonly) four bytes, with a range in the billions either side of zero; a decimal put into an int is **cut, not rounded** — 3.9 becomes 3 — which is either the programmer's intention or their quietest bug. Variables are declared with their type before use: `int marks; char grade;` — C checks types as it compiles, and its complaints are the type system standing guard.

[Picture — char and int — characters and whole numbers]

## Sub lesson 2 — float and double — decimals, at two precisions; and format specifiers

Decimals live in **float** (single precision, four bytes, about seven trustworthy digits) and **double** (double precision, eight bytes, about fifteen) — the money, measurements and science types, chosen by how much exactness the work deserves. Each type has its **format specifier** for printf and scanf: **%d** for int, **%c** for char, **%f** for float and double in printing — the specifier is the promise the programmer makes about what is coming, and a lying specifier prints garbage from honest data. Type, declaration, specifier: the three agreements this lesson binds together.

[Picture — float and double — decimals, at two precisions; and format specifiers]

## Say it to your companion

Tell your companion, in your own words: The **char** type holds **one character** — one byte — stored as its code number (the character-codes lesson): 'A' is kept as 65. The **int** type holds **whole numbers** — counts, ages, marks — in (commonly) four bytes, with a range in the billions either side of zero; a decimal put into an int is **cut, not rounded** — 3.9 becomes 3 — which is either the programmer's intention or their quietest bug. Variables are declared with their type before use: `int marks; char grade;` — C checks types as it compiles, and its complaints are the type system standing guard. Decimals live in **float** (single precision, four bytes, about seven trustworthy digits) and **double** (double precision, eight bytes, about fifteen) — the money, measurements and science types, chosen by how much exactness the work deserves. Each type has its **format specifier** for printf and scanf: **%d** for int, **%c** for char, **%f** for float and double in printing — the specifier is the promise the programmer makes about what is coming, and a lying specifier prints garbage from honest data. Type, declaration, specifier: the three agreements this lesson binds together. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One character — stored as its code number. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: As 65, its code. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Whole numbers. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It is cut to 3, not rounded. Do this with a real example of your own and write or say how you know it is right.
