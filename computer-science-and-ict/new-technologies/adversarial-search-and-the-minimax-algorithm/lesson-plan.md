# Lesson plan — Adversarial Search and the Minimax Algorithm

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Adversarial Search and the Minimax Algorithm
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T2 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** adversarial search — searching when an opponent searches against you — and the minimax algorithm (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Adversarial search — two wills in one tree** — **Adversarial search** studies games as search trees where two players alternate: **MAX**, who wants the highest final score, and **MIN**, who wants it lowest. A position's value is no longer found but **fought over**: MAX chooses the move leading to the best value she can force; MIN chooses the move leading to the worst for her. The tree's leaves are scored by a **utility function** — win, loss, draw, or a number.
2. **Minimax — assuming the worst, playing the best** — The **minimax algorithm** values a position by supposing both play perfectly: at MAX's nodes take the **maximum** of the children's values, at MIN's nodes the **minimum**, working up from the leaves — and MAX then chooses the move whose minimax value is highest. Jordan's Grade 12 lesson programs it in Python for tic-tac-toe (the next programming lesson): a game small enough to search whole, teaching the shape every game AI — chess engines included — still stands on, pruned and heuristically trimmed.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An opponent searches against you — the world moves back
2. The player wanting the highest score, and the one wanting it lowest
3. The move leading to the worst value for MAX
4. A utility function — win, loss, draw, or a number

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every search so far had a passive world. In a game, the world moves back — and chooses the move you like least. This lesson learns to search against an enemy. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of adversarial search — two wills in one tree as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of minimax — assuming the worst, playing the best in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of adversarial search — two wills in one tree → the student studies the picture and names what each part shows
- GIF — a GIF of minimax — assuming the worst, playing the best in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
