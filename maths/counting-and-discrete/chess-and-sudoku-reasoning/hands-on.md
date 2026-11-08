# Hands-on — Chess and Sudoku Reasoning

## Activity 1 — Prove the back-rank mate, then break it (10 minutes)

Set up: White — king g1, rook a1, pawns f2, g2, h2. Black — king h8, pawns g7, h7. White to move. Find the mate in one (1. Ra8#), then write the proof in three lines: one line for why the king cannot move (g8 is guarded by the rook along the rank; g7 and h7 are occupied by its own pawns), one for why nothing can block, one for why nothing can capture the rook. Now move the black pawn from g7 to g6 and try again: 1. Ra8+ is no longer mate — find the king's escape (g7: the rook guards only the eighth rank and the a-file, and nothing white attacks g7). The pawn's square was part of the mate.

## Activity 2 — Solve the mini-sudoku by elimination only (15 minutes)

Draw the 4×4 grid (digits 1–4, 2×2 boxes):

```
1 . 3 .
. 4 . 2
2 . 4 .
. 3 . 1
```

Before placing anything, pencil the candidates into the top row's second cell from its row (2 or 4) and its column (1 or 2), and circle the survivor (2). Continue, one forced cell at a time, writing the reason beside each placement — row, column or box. You should finish at 1234 / 3412 / 2143 / 4321 with no guess anywhere. This is the small training form of the 9×9 sudoku Bolivia's laboratory sets (Secundaria 1 and 2 sections of the teacher compendium, printed pp. 82 and 80).

## Activity 3 — Rehearse a mate in two (15 minutes)

Set up: White — king g6, queen b1. Black — king h8, rook a8. Your job is the full method, on paper: (1) find the checking first move 1. Qb2+; (2) list EVERY legal black reply — there is exactly one (Kg8), because the white king covers g7 and h7, and the rook on a8 can neither block the b2–h8 diagonal (its squares are c3, d4, e5, f6, g7, none on the rook's rank or file) nor capture the queen; (3) give the mate (2. Qg7#, queen protected by the king on g6). Then try to break your own solution: could 1. Qb8+ have been mate at once instead? (No — the rook simply captures her: 1... Rxb8.) Compare with the mate-in-two puzzles of Chess VI in the compendium's Secundaria 6 section (printed p. 172).
