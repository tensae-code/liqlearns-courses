# Combining Functions and Arrays

## Do it first

This is where the theme's two halves join: the array becomes something functions can be handed, and whole programs take their final shape.

## Sub lesson 1 — Passing an array to a function

A function declares an array parameter as **int a[]** (size left open) and — because the function cannot see how many elements are live — the **count n travels with it**: **void printArray(int a[], int n)**. Inside, the function indexes the parameter exactly like a local array. Unlike ordinary variables, **no copy** is made: the function works on the caller's own elements.

[Picture — passing an array to a function]

## Sub lesson 2 — The capstone shape — fill, process, print

Because changes are real, the theme's programs settle into a standard crew: a **fill** function reads the array, **process** functions (total, crown, count, transform) work on it, a **print** function shows it, and **main** only calls the crew in order. That is modular programming standing on arrays — the Year 2 book's destination for its whole C++ theme, and the shape its final exercises demand.

[Picture — the capstone shape — fill, process, print]

## Say it to your companion

Tell your companion, in your own words: Functions and arrays meet through parameters: an array is handed to a function together with its live count, and the function works on the caller's actual array — no copy is made — so the capstone pattern of the theme is a program split into functions that fill, process and print one shared array. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: int a[] — with the size left open. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The function cannot see how many elements are live. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Fill, process and print. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No copy — the caller's own elements are changed. Do this with a real example of your own and write or say how you know it is right.
