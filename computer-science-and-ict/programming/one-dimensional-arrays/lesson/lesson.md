# One-Dimensional Arrays

## Do it first

Fifty test scores need fifty variables — or one array. This lesson replaces the crowd of variables with a single row the program can walk along.

## Sub lesson 1 — One name, many elements

An **array** declares a **type**, one **name** and a **size**: int scores[5] makes five integer **elements** in a row, stored side by side in memory. Every element is a full variable of the array's type — it can be assigned, read and computed with — and the array's gift is that the **position** selecting the element can itself be a variable, which no list of separate names can do.

[Picture — one name, many elements]

## Sub lesson 2 — Why arrays change what programs can do

Because position can be computed, a **loop** can visit every element with the same code: read all, print all, total all. Without arrays, each of fifty scores would need its own lines of code; with an array, five lines serve five elements or five thousand. That is why the book gives arrays a long run of sections — the array is the first **data structure** a C++ programmer meets.

[Picture — why arrays change what programs can do]

## Say it to your companion

Tell your companion, in your own words: A one-dimensional array is a single row of same-type values stored together under one name, each value in its own numbered element — one variable holding many values, reachable by position, which is what lets a loop process a whole collection with a few lines. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A type, one name and a size. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Side by side in memory, in one row. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A loop. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The same few lines that serve five. Do this with a real example of your own and write or say how you know it is right.
