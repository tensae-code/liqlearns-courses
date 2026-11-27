# The N-Queens Problem

## Do it first

the N-queens problem — placing N queens on an N×N board so none attacks another, solved by backtracking row by row (Vietnam Grade 11 specialist, CS)

## Sub lesson 1 — The problem — queens that must not meet

The **queens problem** (bài toán xếp Hậu): place **N queens on an N×N chessboard** so that **no queen attacks another** — no two share a **row, a column, or a diagonal**. Small boards teach humility: N=2 and N=3 have **no solution at all**, N=4 has one essentially, and N=8 — the classic — has 92. Vietnam's specialist book closes its backtracking strand with this problem because every part of the technique is visible in it: the choices, the conditions, and the stepping back.

In your mind's eye: the problem — queens that must not meet.

[Picture 47856 — the problem — queens that must not meet]

## Sub lesson 2 — The solution — one queen per row, checked at once

Backtracking simplifies the problem with one decision: place queens **row by row** — one queen in each row — so rows can never clash, and only **columns and diagonals** need checking. Place the row's queen in the first free column that passes the checks, move to the next row; if a row has **no safe column**, backtrack — move the previous row's queen to her next column and descend again. A full board is a solution; exhausting row one's columns proves none exists.

In your mind's eye: the solution — one queen per row, checked at once.

[Picture 47857 — the solution — one queen per row, checked at once]

## Say it to your companion

Tell your companion, in your own words: The **queens problem** (bài toán xếp Hậu): place **N queens on an N×N chessboard** so that **no queen attacks another** — no two share a **row, a column, or a diagonal**. Small boards teach humility: N=2 and N=3 have **no solution at all**, N=4 has one essentially, and N=8 — the classic — has 92. Vietnam's specialist book closes its backtracking strand with this problem because every part of the technique is visible in it: the choices, the conditions, and the stepping back. Backtracking simplifies the problem with one decision: place queens **row by row** — one queen in each row — so rows can never clash, and only **columns and diagonals** need checking. Place the row's queen in the first free column that passes the checks, move to the next row; if a row has **no safe column**, backtrack — move the previous row's queen to her next column and descend again. A full board is a solution; exhausting row one's columns proves none exists. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Any two queens sharing a row, a column, or a diagonal Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: N = 2 and N = 3 Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 92 Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Every part of backtracking is visible in it — choices, conditions, stepping back Do this with a real example of your own and write or say how you know it is right.
