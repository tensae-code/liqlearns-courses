# Programming a Tic-Tac-Toe Game in Python

## Do it first

The AI unit ends at the board: nine squares, two players, and a program that plays back — with the minimax of the search lessons as its brain. This lesson builds it.

## Sub lesson 1 — The game as a program

The board is **data**: nine cells in a list, each empty, X or O. The program's working: **display** the board, take a **move** (and refuse illegal ones — occupied, outside), **place** the mark, **test the end** — a completed line (rows, columns, diagonals) wins; a full board draws — and **change the turn**. Every part is a function the earlier lessons built: the game is the Python course, assembled on a board small enough to hold in the head entire.

In your mind's eye: the game as a program.

## Sub lesson 2 — The computer opponent — minimax at work

The computer's move is chosen by **adversarial search**: the current board is a state, legal moves are its children, and **minimax** — with the computer as MAX and the player as MIN — values each move by the best outcome the computer can force. Tic-tac-toe's tree is small enough to search whole, so the minimax opponent **never loses** — the pupil can verify the claim by playing, which is why Jordan chooses this game: the theory of the search lessons becomes an opponent you can test with your own hand, and try, and fail, to beat.

In your mind's eye: the computer opponent — minimax at work.

## Say it to your companion

Tell your companion, in your own words: The board is **data**: nine cells in a list, each empty, X or O. The program's working: **display** the board, take a **move** (and refuse illegal ones — occupied, outside), **place** the mark, **test the end** — a completed line (rows, columns, diagonals) wins; a full board draws — and **change the turn**. Every part is a function the earlier lessons built: the game is the Python course, assembled on a board small enough to hold in the head entire. The computer's move is chosen by **adversarial search**: the current board is a state, legal moves are its children, and **minimax** — with the computer as MAX and the player as MIN — values each move by the best outcome the computer can force. Tic-tac-toe's tree is small enough to search whole, so the minimax opponent **never loses** — the pupil can verify the claim by playing, which is why Jordan chooses this game: the theory of the search lessons becomes an opponent you can test with your own hand, and try, and fail, to beat. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Nine cells in a list — empty, X or O. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Display, take a move, place the mark, test the end, change the turn. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Occupied cells and moves outside the board. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Rows, columns and diagonals. Do this with a real example of your own and write or say how you know it is right.
