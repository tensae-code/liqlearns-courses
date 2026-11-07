# Hands-on — Determinants and Cramer's Rule

## Diagonals on paper
Draw a 2×2 grid and fill it with four numbers from your room — say the counts of chairs, tables, doors and windows. Draw the two diagonals in two colours. Main diagonal product minus other diagonal product: that is your determinant, the way Kuwait's book introduces it (Grade 10 Term 2, Lesson 7-4, pp.74–78).

## Sarrus with strips
Write a 3×3 determinant on a wide strip of paper and tape two extra columns — copies of the first two — onto its right edge, the way Nicaragua's book draws Sarrus' rule (printed pp.233–234). Run a ruler down the three falling diagonals and add; run it up the three rising diagonals and subtract. Peel the strips off and check the same determinant by cofactor expansion along the first row.

## Two roads, one answer
Solve x + y = 3, x − y = 7 twice: once by Cramer's rule, once by the inverse matrix — Kuwait's book teaches both in one lesson (Lesson 7-5, pp.79–82), and both roads end at (5, −2). Check by putting the answer back into both equations.

## Code a word
Take the coding matrix A = [[2, 1], [1, 1]]; its inverse is [[1, −1], [−1, 2]]. Turn the letters H and I into the numbers 8 and 9, multiply the column (8, 9) by A to get the coded pair (25, 17), swap coded pairs with a partner, and decode with A⁻¹ to get the letters back — Nicaragua's closing application (Grade 10, printed pp.243–244).
