# Defining Constants in Pascal and C++

## Do it first

Some values in a program are facts, not data: π, the maximum mark, the class size. Writing them as bare numbers everywhere is asking for inconsistency. Grade 10's data chapter closes with the named constant.

## Sub lesson 1 — const — a name whose value is fixed

A **constant definition** binds a **name to a value that never changes** in the run. Pascal gathers them in a **const section**: `const pi = 3.14159; maxMark = 10;` — the type follows from the value written. C++ writes **`const`** before a typed declaration: `const double pi = 3.14159;` (its older #define also names constants, without a type). Using the name where the value belongs makes the compiler the guard: an assignment to a constant is an **error**, not a temptation.

[Picture — const — a name whose value is fixed]

## Sub lesson 2 — Why constants — one truth, everywhere

The reasons echo the type chapter's: **readability** (maxMark speaks; 10 is silent), **one place of truth** (the tax rate changes once, in the const section — not in forty hunted lines), and **safety** (a value the program must not alter is made unalterable). Constants, types and declarations together are the program's front matter: read them and the data's whole constitution is known before the first instruction. Grade 10's data theory ends here — with the program fully described before it acts.

[Picture — Why constants — one truth, everywhere]

## Say it to your companion

Tell your companion, in your own words: A **constant definition** binds a **name to a value that never changes** in the run. Pascal gathers them in a **const section**: `const pi = 3.14159; maxMark = 10;` — the type follows from the value written. C++ writes **`const`** before a typed declaration: `const double pi = 3.14159;` (its older #define also names constants, without a type). Using the name where the value belongs makes the compiler the guard: an assignment to a constant is an **error**, not a temptation. The reasons echo the type chapter's: **readability** (maxMark speaks; 10 is silent), **one place of truth** (the tax rate changes once, in the const section — not in forty hunted lines), and **safety** (a value the program must not alter is made unalterable). Constants, types and declarations together are the program's front matter: read them and the data's whole constitution is known before the first instruction. Grade 10's data theory ends here — with the program fully described before it acts. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A name bound to a value that never changes in the run. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In a const section. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: With const before the declaration — const double pi = 3.14159;. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A compile error — the compiler guards the name. Do this with a real example of your own and write or say how you know it is right.
