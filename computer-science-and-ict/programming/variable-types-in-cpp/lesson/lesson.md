# Variable Types in C++

## Do it first

A variable is not just a name — it is a name with a kind. This lesson is about the kinds C++ starts with, split out from the variables lesson by the book's own section.

## Sub lesson 1 — The four starter types

**int** holds **whole numbers** in a limited range; **double** holds numbers **with fractions**, approximately, across a huge range; **char** holds **one character** (a letter, digit or symbol, stored as a code); **bool** holds exactly **true or false**. Declaring `int age;` reserves int-sized memory under the name age and forbids text from living there.

[Picture — the four starter types]

## Sub lesson 2 — Type decides behaviour

The type steers the operations: int division **drops fractions**, double division keeps them; adding to a char moves its **code** ('A' + 1 is 'B'); a bool is what conditions test. Giving a value to the wrong type converts or refuses it — 3.9 poured into an int becomes **3** — so choosing the type is the first design decision for every value in the program.

[Picture — type decides behaviour]

## Say it to your companion

Tell your companion, in your own words: Every C++ variable has a type that fixes what kind of value it holds and how much memory it takes: int for whole numbers, double for numbers with fractions, char for a single character and bool for true/false — and the type decides which operations make sense and what happens at its edges. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The kind of value it holds and its memory size. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: char. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Drops them. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A bool — true or false. Do this with a real example of your own and write or say how you know it is right.
