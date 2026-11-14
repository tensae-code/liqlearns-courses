# Working with Files in Pascal

## Do it first

A program that forgets everything at shutdown can only play. With files, Pascal keeps its data on disk between runs — Grade 9's lesson on working with files, near the end of the course.

## Sub lesson 1 — Assign, reset, rewrite — opening a file

File work starts by joining a **file variable** to a real file with **assign**, then opening it: **reset** opens an existing file for reading, **rewrite** creates or empties a file for writing. Reading and writing then move value by value with read and write on the file. The name on disk and the name in the program are two names for one stream of data.

[Picture — Assign, reset, rewrite — opening a file]

## Sub lesson 2 — Reading to the end, and closing

A reading program cannot know a file's length in advance, so it reads **until eof** — the end-of-file test — is true. Every opened file ends with **close**: closing writes the last values safely and frees the file for others. The book places files after graphics and before procedures — the course's data now outlives the program that made it.

[Picture — Reading to the end, and closing]

## Say it to your companion

Tell your companion, in your own words: File work starts by joining a **file variable** to a real file with **assign**, then opening it: **reset** opens an existing file for reading, **rewrite** creates or empties a file for writing. A reading program cannot know a file's length in advance, so it reads **until eof** — the end-of-file test — is true. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: assign. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: reset. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: eof — the end-of-file test. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The file was written by earlier runs or other programs. Do this with a real example of your own and write or say how you know it is right.
