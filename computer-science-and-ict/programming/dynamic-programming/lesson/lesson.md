# Dynamic Programming

## Do it first

Dynamic programming — solving a problem whose pieces overlap by solving each small piece once, storing its answer, and building the whole from the stored answers

## Sub lesson 1 — The waste it removes — solving the same piece twice

Some problems split into pieces that **overlap**: the pieces share smaller pieces, so a plain recursive attack solves the same small problem again and again — the work explodes while the answers repeat. **Dynamic programming** (pemrograman dinamis) is the discipline that refuses the waste: solve each distinct small piece **once**, **store** its answer in a table, and let every bigger piece **read** the stored answer instead of solving again. Indonesia's Grade 11 algorithm chapter teaches it as the third of its advanced strategies, after recursion and greedy — the strategy for problems whose shape is a family of overlapping subproblems.

[Picture — The waste it removes — solving the same piece twice]

## Sub lesson 2 — Building the table — smallest first

The method has a working order: name the **subproblems** (what exactly a small piece asks), solve them **smallest first** so every answer a bigger piece needs is already in the table, and state the **joining rule** — how a piece's answer is built from the smaller answers beneath it. Its price is memory (the table) and its profit is time (each piece solved once), and its tell is the question a programmer learns to ask of any slow recursion: 'am I solving this piece before?' — where the answer is yes, a table is waiting to be built.

[Picture — Building the table — smallest first]

## Say it to your companion

Tell your companion, in your own words: Some problems split into pieces that **overlap**: the pieces share smaller pieces, so a plain recursive attack solves the same small problem again and again — the work explodes while the answers repeat. **Dynamic programming** (pemrograman dinamis) is the discipline that refuses the waste: solve each distinct small piece **once**, **store** its answer in a table, and let every bigger piece **read** the stored answer instead of solving again. Indonesia's Grade 11 algorithm chapter teaches it as the third of its advanced strategies, after recursion and greedy — the strategy for problems whose shape is a family of overlapping subproblems. The method has a working order: name the **subproblems** (what exactly a small piece asks), solve them **smallest first** so every answer a bigger piece needs is already in the table, and state the **joining rule** — how a piece's answer is built from the smaller answers beneath it. Its price is memory (the table) and its profit is time (each piece solved once), and its tell is the question a programmer learns to ask of any slow recursion: 'am I solving this piece before?' — where the answer is yes, a table is waiting to be built. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A problem whose pieces overlap — the pieces share smaller pieces Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Solving the same small problem again and again Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Solves each distinct small piece once, stores its answer in a table, and reads it back Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: How a piece's answer is built from the smaller answers beneath it Do this with a real example of your own and write or say how you know it is right.
