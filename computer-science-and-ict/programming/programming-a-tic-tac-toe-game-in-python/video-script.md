# Video script — Programming a Tic-Tac-Toe Game in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The board is **data**: nine cells in a list, each empty, X or O. The program's working: **display** the board, take a **move** (and refuse illegal ones — occupied, outside), **place** the mark, **test the end** — a completed line (rows, columns, diagonals) wins; a full board draws — and **change the turn**. Every part is a function the earlier lessons built: the game is the Python course, assembled on a board small enough to hold in the head entire.
The computer's move is chosen by **adversarial search**: the current board is a state, legal moves are its children, and **minimax** — with the computer as MAX and the player as MIN — values each move by the best outcome the computer can force. Tic-tac-toe's tree is small enough to search whole, so the minimax opponent **never loses** — the pupil can verify the claim by playing, which is why Jordan chooses this game: the theory of the search lessons becomes an opponent you can test with your own hand, and try, and fail, to beat.
