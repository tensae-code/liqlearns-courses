# Video script — The N-Queens Problem

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **queens problem** (bài toán xếp Hậu): place **N queens on an N×N chessboard** so that **no queen attacks another** — no two share a **row, a column, or a diagonal**. Small boards teach humility: N=2 and N=3 have **no solution at all**, N=4 has one essentially, and N=8 — the classic — has 92. Vietnam's specialist book closes its backtracking strand with this problem because every part of the technique is visible in it: the choices, the conditions, and the stepping back.
Backtracking simplifies the problem with one decision: place queens **row by row** — one queen in each row — so rows can never clash, and only **columns and diagonals** need checking. Place the row's queen in the first free column that passes the checks, move to the next row; if a row has **no safe column**, backtrack — move the previous row's queen to her next column and descend again. A full board is a solution; exhausting row one's columns proves none exists.
