# Ordering — Chess and Sudoku Reasoning

1. (Layer 2) Put the steps of the mate-in-one candidate check in order:
   (a) for one checking move, test whether the king can move to a safe square
   (b) list all of your checking moves
   (c) if moving, blocking and capturing all fail, the move is checkmate
   (d) test whether anything can block the check or capture the attacker

   **Answer: (b), (a), (d), (c)** — enumerate checks first, then run the three exits in order; mate is the verdict only when all three fail. Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 section, printed p. 82 (Chess I, mate-in-one exercises).

2. (Layer 3) Put the deduction for the top row's second cell of the lesson's 4×4 mini-sudoku (top row `1 . 3 .`, second column holding 4 and 3) in order:
   (a) the column allows only 1 or 2 for this cell
   (b) the row allows only 2 or 4 for this cell
   (c) write 2 in the cell
   (d) the only digit in both lists is 2

   **Answer: (b), (a), (d), (c)** — intersect the row's candidates with the column's; the single survivor is forced (the box agrees). Training grid constructed for this lesson; the sudoku strand is Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 section, printed p. 82.
