# Lesson plan — The N-Queens Problem

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The N-Queens Problem
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 11 Chuyên đề Tin học 11 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the N-queens problem — placing N queens on an N×N board so none attacks another, solved by backtracking row by row (Vietnam Grade 11 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The problem — queens that must not meet** — The **queens problem** (bài toán xếp Hậu): place **N queens on an N×N chessboard** so that **no queen attacks another** — no two share a **row, a column, or a diagonal**. Small boards teach humility: N=2 and N=3 have **no solution at all**, N=4 has one essentially, and N=8 — the classic — has 92. Vietnam's specialist book closes its backtracking strand with this problem because every part of the technique is visible in it: the choices, the conditions, and the stepping back.
2. **The solution — one queen per row, checked at once** — Backtracking simplifies the problem with one decision: place queens **row by row** — one queen in each row — so rows can never clash, and only **columns and diagonals** need checking. Place the row's queen in the first free column that passes the checks, move to the next row; if a row has **no safe column**, backtrack — move the previous row's queen to her next column and descend again. A full board is a solution; exhausting row one's columns proves none exists.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Any two queens sharing a row, a column, or a diagonal
2. N = 2 and N = 3
3. 92
4. Every part of backtracking is visible in it — choices, conditions, stepping back

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — the N-queens problem — placing N queens on an N×N board so none attacks another, solved by backtracking row by row (Vietnam Grade 11 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the problem — queens that must not meet as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the solution — one queen per row, checked at once in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the problem — queens that must not meet → the student studies the picture and names what each part shows
- GIF — a GIF of the solution — one queen per row, checked at once in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
