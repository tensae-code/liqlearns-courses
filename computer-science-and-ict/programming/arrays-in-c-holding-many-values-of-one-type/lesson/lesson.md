# Arrays in C — Holding Many Values of One Type

## Do it first

Thirty students, thirty marks. Declare thirty variables and your program drowns in names before it computes anything. The array is the rescue: one name, thirty numbered rooms. In C the rescue comes with C's honesty — fixed size, no mercy at the edges — and both halves are this lesson.

## Sub lesson 1 — Declaring and initialising — one name, many rooms

An **array** holds **many values of one type** under **one name**: `int marks[30];` declares thirty int rooms. It may be **initialised** at birth with a list — `int days[7] = {31, 28, 31, 30, 31, 30, 31};` — and its size is fixed at declaration: C arrays do not grow. The type rule is strict — every room holds the array's one type — which is the array's bargain: order and speed in exchange for sameness.

In your mind's eye: declaring and initialising — one name, many rooms.

[Picture 46722 — declaring and initialising — one name, many rooms]

## Sub lesson 2 — Indexing — counting from zero, and the edge

Rooms are reached by **index**: `marks[0]` is the **first** room, `marks[29]` the thirtieth and last — C counts from **zero**, so the last index is always **size − 1**. The loop and the array are made for each other: a for loop walking i from 0 to size−1 visits every room exactly once, which is how arrays are filled, summed and searched (the linear-search placement's home ground). The edge is unforgiving: C does **not check** an index — `marks[30]` reaches into memory that is not yours and reads or writes a stranger's value silently. The boundary is the programmer's own discipline: the loop's condition is the fence, and it must be written like one.

In your mind's eye: indexing — counting from zero, and the edge.

[Picture 46723 — indexing — counting from zero, and the edge]

## Say it to your companion

Tell your companion, in your own words: An **array** holds **many values of one type** under **one name**: `int marks[30];` declares thirty int rooms. It may be **initialised** at birth with a list — `int days[7] = {31, 28, 31, 30, 31, 30, 31};` — and its size is fixed at declaration: C arrays do not grow. The type rule is strict — every room holds the array's one type — which is the array's bargain: order and speed in exchange for sameness. Rooms are reached by **index**: `marks[0]` is the **first** room, `marks[29]` the thirtieth and last — C counts from **zero**, so the last index is always **size − 1**. The loop and the array are made for each other: a for loop walking i from 0 to size−1 visits every room exactly once, which is how arrays are filled, summed and searched (the linear-search placement's home ground). The edge is unforgiving: C does **not check** an index — `marks[30]` reaches into memory that is not yours and reads or writes a stranger's value silently. The boundary is the programmer's own discipline: the loop's condition is the fence, and it must be written like one. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Many values of one type under one name. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: int marks[30];. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — its size is fixed. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A list of values in braces. Do this with a real example of your own and write or say how you know it is right.
