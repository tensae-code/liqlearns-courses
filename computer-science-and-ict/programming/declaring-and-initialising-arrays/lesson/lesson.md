# Declaring and Initialising Arrays

## Do it first

An array starts life somehow — empty, or already holding values. This lesson covers both births, and what each element holds in each case.

## Sub lesson 1 — Declaring — type, name, size

The declaration **int a[5];** reserves five integer elements. The **size** must be a whole number known when the program is written (in this book's C++, a constant). Declaring alone leaves the elements **uninitialised** — they hold whatever was in memory — so a careful program never reads an element before giving it a value.

[Picture — declaring — type, name, size]

## Sub lesson 2 — Initialising — braces at birth

**int a[5] = {10, 20, 30, 40, 50};** fills the elements **in order**. A **shorter list** fills the front and **zeroes the rest**: {10, 20} leaves 10, 20, 0, 0, 0. **int a[] = {7, 8, 9};** omits the size and the list sets it to 3. Listing **more** values than the size is an error the compiler catches.

[Picture — initialising — braces at birth]

## Say it to your companion

Tell your companion, in your own words: An array is declared with its type, name and size in square brackets, and it can be initialised at birth with a list of values in braces — matching values fill elements in order, a shorter list leaves the rest at zero, and leaving the size out lets the list itself set it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Type, name and size. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Whatever was in memory — garbage. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: In order, from the first element. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: An array of size 3. Do this with a real example of your own and write or say how you know it is right.
