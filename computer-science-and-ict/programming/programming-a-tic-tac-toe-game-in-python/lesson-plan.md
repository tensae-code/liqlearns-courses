# Lesson plan — Programming a Tic-Tac-Toe Game in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Programming a Tic-Tac-Toe Game in Python
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T2 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** programming the XO (tic-tac-toe) game in Python — the board, the moves, the win, and the minimax opponent (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The game as a program** — The board is **data**: nine cells in a list, each empty, X or O. The program's working: **display** the board, take a **move** (and refuse illegal ones — occupied, outside), **place** the mark, **test the end** — a completed line (rows, columns, diagonals) wins; a full board draws — and **change the turn**. Every part is a function the earlier lessons built: the game is the Python course, assembled on a board small enough to hold in the head entire.
2. **The computer opponent — minimax at work** — The computer's move is chosen by **adversarial search**: the current board is a state, legal moves are its children, and **minimax** — with the computer as MAX and the player as MIN — values each move by the best outcome the computer can force. Tic-tac-toe's tree is small enough to search whole, so the minimax opponent **never loses** — the pupil can verify the claim by playing, which is why Jordan chooses this game: the theory of the search lessons becomes an opponent you can test with your own hand, and try, and fail, to beat.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Nine cells in a list — empty, X or O
2. Display, take a move, place the mark, test the end, change the turn
3. Occupied cells and moves outside the board
4. Rows, columns and diagonals

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The AI unit ends at the board: nine squares, two players, and a program that plays back — with the minimax of the search lessons as its brain. This lesson builds it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the game as a program as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the computer opponent — minimax at work in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the game as a program → the student studies the picture and names what each part shows
- GIF — a GIF of the computer opponent — minimax at work in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
