# Chess and Sudoku Reasoning

## You do it first

A black king sits on h8, the corner square. Its own pawns stand on g7 and h7, right in front of it. A white rook stands far away on a1, and it is White to move. White can give check — and it is not just check. Can you see why the black king is already trapped?

Hold your answer. By the end of this lesson you will be able to prove it, square by square.

## The laboratory idea

Bolivia's official school books do something unusual: they end their year sections with a *Laboratorio matemático* — a mathematics laboratory — where the exercises are not calculations at all but chess problems and sudoku, set as logic training. The laboratory appears in four of the six Secundaria years of the ministry's teacher compendium of the student texts: Chess I and Sudoku in the first year, Chess II and Sudoku in the second, Chess V in the fifth, and Chess VI — advanced rules and mate-in-two puzzles — in the sixth. (Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 (Grade 7) section, printed p. 82; Secundaria 2 (Grade 8) section, printed p. 80; Secundaria 5 (Grade 11) section, printed p. 171; Secundaria 6 (Grade 12) section, printed p. 172.) The skill being trained is one and the same in both games: list what is possible, test every possibility against every rule, and keep only what survives.

## The board and the pieces

The chessboard is an 8×8 grid: **files** (columns) lettered a to h, **ranks** (rows) numbered 1 to 8, so every square has a name — a1 is a corner, h8 the opposite one. The pieces move like this: the **king** steps one square in any direction; the **queen** slides any distance along ranks, files and diagonals; the **rook** slides along ranks and files only; the **bishop** slides along diagonals only; the **knight** jumps in an L — two squares straight and one to the side — and is the only piece that can jump over others; the **pawn** steps forward, and captures one square diagonally forward.

A king is in **check** when an enemy piece attacks its square. A king is in **checkmate** when it is in check and has no way out. There are only ever three ways out: **move** the king to a safe square, **block** the attack with a piece of your own, or **capture** the attacking piece. If none of the three works, the game is over. (Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 (Grade 7) section, printed p. 82 — Chess I, basic notions.)

## Mate in one: the candidate check

To find a mate in one, do not guess — enumerate. First list your **checking moves**: the moves that give check. There are usually only a few. For each one, test the king's three exits in order: can it move (check every square around it — is each one attacked or occupied by its own pieces)? Can anything block? Can anything capture the attacker, and is the attacker protected?

Now the position from the start of the lesson. White plays **1. Ra8+** — the rook slides the length of the board to a8 and checks along the eighth rank. Can the king move? g8 is attacked by the rook along the rank; g7 and h7 are occupied by the king's own pawns — his own pieces close his exits. Can anything block a rook already standing next door on the same rank? No black piece can reach the line. Can anything capture the rook on a8? Nothing black is near it. All three exits fail: **Ra8 is checkmate.** This is the famous back-rank mate, and the lesson of it is the method: the mate was proven by exhausting the exits, not spotted by luck. (Position constructed for this lesson in the style of the mate-in-one exercises of Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 (Grade 7) section, printed p. 82.)

One more, with the queen. White: king on f6, queen on g5. Black: king on h8. **1. Qg7#** — the queen steps to g7, next to the black king, and checks it diagonally. The king cannot capture her: the white king on f6 protects g7. The king cannot move: g8 and h7 are both attacked by the queen. Nothing can block a queen standing adjacent, and nothing else black exists to capture her. Mate — again proven by the three exits. (Position constructed for this lesson in the style of the mate-in-one exercises of Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 (Grade 7) section, printed p. 82.)

## Mate in two: one reply deep

A mate in two demands one more layer: your first move is not mate, so the defender replies — and you must already hold a mate against **every** legal reply, not just the obvious one. The method grows by one step: find a checking first move, list **all** the defender's replies, and find a mate for each. If even one reply has no mate, the first move is wrong — discard it and look again. (Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 6 (Grade 12) section, printed p. 172 — Chess VI, mate-in-two puzzles.)

Worked example. White: king on g6, queen on b1. Black: king on h8 and a rook on a8. Try **1. Qb2+** — check along the long diagonal b2–h8. Now enumerate Black's replies, all of them. The king's neighbours: g8, g7, h7 — the white king on g6 attacks g7 and h7, and the queen now attacks g7 too, so exactly one king move exists: g8. Can the rook save him? To block the diagonal it would have to land on c3, d4, e5, f6 or g7, and a rook on a8 — moving only along the eighth rank and the a-file — reaches none of those squares. Can the rook capture the queen on b2? It cannot reach her either. So Black has exactly one legal reply: **1... Kg8**. Against it, **2. Qg7#**: the queen comes to g7, protected by her king on g6, checking the king on g8 from beside it; the king's exits — h8 and f8 — are attacked by the queen, f7 and h7 are held by the white king, and the rook can neither capture on g7 (not on any of its lines) nor block a check delivered from the next square. Every reply (all one of them) is mated, so the mate in two is proven. (Position constructed for this lesson in the style of the mate-in-two puzzles of Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 6 (Grade 12) section, printed p. 172.)

Notice what made the proof short: the defender had very few legal replies, and the solver's job was to count them all. That counting is the whole skill — the same discipline the chess laboratory keeps raising, from Chess I's mate-in-one exercises to Chess VI's advanced rules and mate-in-two puzzles. (Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 2 (Grade 8) section, printed p. 80; Secundaria 5 (Grade 11) section, printed p. 171; Secundaria 6 (Grade 12) section, printed p. 172.)

## Sudoku: elimination on a grid

Sudoku is the same reasoning wearing a grid. The board is 9×9, split into nine 3×3 **boxes**; every **row**, every **column** and every **box** must end up holding the digits 1 to 9 exactly once. You are given some digits; the rest must be deduced — never guessed. (Bolivia, *Compendio para Maestras y Maestros 2023–2024* (teacher compendium), Secundaria 1 (Grade 7) section, printed p. 82; Secundaria 2 (Grade 8) section, printed p. 80.)

Two tools do most of the work. A **single candidate**: look at one empty cell and intersect what its row allows, what its column allows and what its box allows — if exactly one digit survives the three cuts, it is forced. A **hidden single**: look at one unit (row, column or box) and one missing digit — if the digit fits in exactly one cell of the unit, it is forced there, even if that cell has other candidates.

Watch the tools on a training board — a 4×4 mini-sudoku with digits 1 to 4 and 2×2 boxes, small enough to check completely:

```
1 . 3 .
. 4 . 2
2 . 4 .
. 3 . 1
```

Take the top row's second cell. Its row already holds 1 and 3, so the cell is 2 or 4. Its column already holds 4 and 3, so the cell is 1 or 2. The only digit in both lists is **2** — a single candidate, forced. Now the third row's second cell: the column now holds 2, 4, 3, so the missing digit is **1** — forced by the column alone. Keep cutting: the second row's first cell must be 3 (its row wants 1 or 3, its column wants 3 or 4), the fourth row's first cell is 4, and the board completes itself: 1234 / 3412 / 2143 / 4321. Every placement was forced; no digit was ever guessed. On the full 9×9 board nothing changes except the size of the lists — the reasoning is identical, and it is exactly the list-and-eliminate discipline the chess half of the laboratory trains: possibilities first, rules applied to all of them, only survivors kept.

## Do it yourself

1. In the back-rank position (White: Kg1, Ra1, pawns f2, g2, h2; Black: Kh8, pawns g7, h7), why would Ra8+ stop being mate if the black pawn stood on g6 instead of g7? (Because g7 becomes an escape square: the rook on a8 attacks only the eighth rank, and nothing white attacks g7, so the king simply steps there.)
2. White: Kg6, Qb1; Black: Kh8, Ra8. A student tries 1. Qh7+?? as the first move of a mate in two. Why is the move impossible? (The queen's path from b1 to h7 runs along the diagonal b1–c2–d3–e4–f5–g6–h7, and her own king stands on g6, in the way.)
3. In the 4×4 mini-sudoku above, after placing 2 and 1 in the second column, which cell is forced next and why? (The fourth row's third cell: its row holds 3 and 1, so it wants 2 or 4; its column already holds 3 and 4, so it wants 1 or 2; the only digit in both lists is 2.)
4. State the three exits you must test before calling any check a checkmate. (The king moves to a safe square; a piece blocks the attack; a piece captures the attacker — mate is when all three fail.)
