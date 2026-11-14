# Adversarial Search and the Minimax Algorithm

## Do it first

Every search so far had a passive world. In a game, the world moves back — and chooses the move you like least. This lesson learns to search against an enemy.

## Sub lesson 1 — Adversarial search — two wills in one tree

**Adversarial search** studies games as search trees where two players alternate: **MAX**, who wants the highest final score, and **MIN**, who wants it lowest. A position's value is no longer found but **fought over**: MAX chooses the move leading to the best value she can force; MIN chooses the move leading to the worst for her. The tree's leaves are scored by a **utility function** — win, loss, draw, or a number.

[Picture — Adversarial search — two wills in one tree]

## Sub lesson 2 — Minimax — assuming the worst, playing the best

The **minimax algorithm** values a position by supposing both play perfectly: at MAX's nodes take the **maximum** of the children's values, at MIN's nodes the **minimum**, working up from the leaves — and MAX then chooses the move whose minimax value is highest. Jordan's Grade 12 lesson programs it in Python for tic-tac-toe (the next programming lesson): a game small enough to search whole, teaching the shape every game AI — chess engines included — still stands on, pruned and heuristically trimmed.

[Picture — Minimax — assuming the worst, playing the best]

## Say it to your companion

Tell your companion, in your own words: **Adversarial search** studies games as search trees where two players alternate: **MAX**, who wants the highest final score, and **MIN**, who wants it lowest. A position's value is no longer found but **fought over**: MAX chooses the move leading to the best value she can force; MIN chooses the move leading to the worst for her. The tree's leaves are scored by a **utility function** — win, loss, draw, or a number. The **minimax algorithm** values a position by supposing both play perfectly: at MAX's nodes take the **maximum** of the children's values, at MIN's nodes the **minimum**, working up from the leaves — and MAX then chooses the move whose minimax value is highest. Jordan's Grade 12 lesson programs it in Python for tic-tac-toe (the next programming lesson): a game small enough to search whole, teaching the shape every game AI — chess engines included — still stands on, pruned and heuristically trimmed. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An opponent searches against you — the world moves back. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The player wanting the highest score, and the one wanting it lowest. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The move leading to the worst value for MAX. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A utility function — win, loss, draw, or a number. Do this with a real example of your own and write or say how you know it is right.
