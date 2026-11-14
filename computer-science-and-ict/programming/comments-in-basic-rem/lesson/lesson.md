# Comments in BASIC — REM

## Do it first

Open a program you wrote last month. If every line is bare code, how long before you remember what it was for? In this lesson you learn BASIC's one-word kindness to your future self: REM.

## Sub lesson 1 — REM — a note the computer ignores

A BASIC program can carry notes to its human readers: any line (or part of a line) beginning with **REM** — short for **remark** — is a **comment**. The computer **ignores** REM lines completely when the program runs: they change nothing, print nothing, compute nothing. They exist for the people — the programmer returning to the program in a month, or another programmer reading it for the first time. Sudan's book gives comments their own short section because a program nobody can read is a program nobody can fix.

[Picture — REM — a note the computer ignores]

## Sub lesson 2 — Writing comments that earn their place

A good REM says **why**, not what: the line `30 LET T = P * R / 100` is clearer with `25 REM T IS THE TAX ON PAY P AT RATE R` than with a remark repeating the arithmetic. Comments belong at the **head of the program** (its name, its job, its writer) and **before any part whose purpose is not obvious**. The rule of proportion is the lesson's rule: comment the thinking, not every line — a program drowned in remarks hides its own code.

[Picture — Writing comments that earn their place]

## Say it to your companion

Tell your companion, in your own words: A BASIC program can carry notes to its human readers: any line (or part of a line) beginning with REM — short for remark — is a comment. A good REM says why, not what: the line `30 LET T = P * R / 100` is clearer with `25 REM T IS THE TAX ON PAY P AT RATE R` than with a remark repeating the arithmetic. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Remark. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Ignores them completely — they change, print and compute nothing. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Why — not a repetition of what the line does. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The program's name, its job and its writer. Do this with a real example of your own and write or say how you know it is right.
