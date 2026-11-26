# Fetching Query Results — fetchone, fetchmany, fetchall

## Do it first

A SELECT run from Python asks the question — but the answer still sits on the cursor, not in the program. Kuwait's Grade 11 teaches the fetching that brings it in: three ways, for three appetites. This lesson is the fetching.

## Sub lesson 1 — The cursor and its rows — answers waiting to be fetched

When Python runs a SELECT, the results wait on the **cursor** — the query's answer, row by row, held by the database side of the connection. **Fetching** moves rows from the cursor into the program, where variables can hold them, loops can walk them, and prints can show them. Until a row is fetched it is not the program's: the query was asked, but nothing was heard.

In your mind's eye: the cursor and its rows — answers waiting to be fetched.

[Picture 46530 — the cursor and its rows — answers waiting to be fetched]

## Sub lesson 2 — fetchone, fetchmany, fetchall — one, some, all

The three fetches differ only in appetite. **fetchone** takes the **next one row** — for questions with a single answer. **fetchmany** takes the **next counted rows** — for answers too big to hold at once, taken in mouthfuls. **fetchall** takes **every remaining row** at once, as a list — right for the course's landmark tables, dangerous for a million-row store. Choosing the fetch is choosing how the program will hold the answer, and Kuwait teaches the choice as part of querying, not after it.

In your mind's eye: fetchone, fetchmany, fetchall — one, some, all.

[Picture 46531 — fetchone, fetchmany, fetchall — one, some, all]

## Say it to your companion

Tell your companion, in your own words: When Python runs a SELECT, the results wait on the **cursor** — the query's answer, row by row, held by the database side of the connection. **Fetching** moves rows from the cursor into the program, where variables can hold them, loops can walk them, and prints can show them. Until a row is fetched it is not the program's: the query was asked, but nothing was heard. The three fetches differ only in appetite. **fetchone** takes the **next one row** — for questions with a single answer. **fetchmany** takes the **next counted rows** — for answers too big to hold at once, taken in mouthfuls. **fetchall** takes **every remaining row** at once, as a list — right for the course's landmark tables, dangerous for a million-row store. Choosing the fetch is choosing how the program will hold the answer, and Kuwait teaches the choice as part of querying, not after it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: On the cursor — the query's answer, held by the database side. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Moves rows from the cursor into the program. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Not the program's — the query was asked but nothing was heard. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The next one row. Do this with a real example of your own and write or say how you know it is right.
