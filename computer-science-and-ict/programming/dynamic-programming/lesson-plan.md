# Lesson plan — Dynamic Programming

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Dynamic Programming
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 11 G11 Informatika student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** dynamic programming — solving a problem whose pieces overlap by solving each small piece once, storing its answer, and building the whole from the stored answers (Indonesia Grade 11).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The waste it removes — solving the same piece twice** — Some problems split into pieces that **overlap**: the pieces share smaller pieces, so a plain recursive attack solves the same small problem again and again — the work explodes while the answers repeat. **Dynamic programming** (pemrograman dinamis) is the discipline that refuses the waste: solve each distinct small piece **once**, **store** its answer in a table, and let every bigger piece **read** the stored answer instead of solving again. Indonesia's Grade 11 algorithm chapter teaches it as the third of its advanced strategies, after recursion and greedy — the strategy for problems whose shape is a family of overlapping subproblems.
2. **Building the table — smallest first** — The method has a working order: name the **subproblems** (what exactly a small piece asks), solve them **smallest first** so every answer a bigger piece needs is already in the table, and state the **joining rule** — how a piece's answer is built from the smaller answers beneath it. Its price is memory (the table) and its profit is time (each piece solved once), and its tell is the question a programmer learns to ask of any slow recursion: 'am I solving this piece before?' — where the answer is yes, a table is waiting to be built.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A problem whose pieces overlap — the pieces share smaller pieces
2. Solving the same small problem again and again
3. Solves each distinct small piece once, stores its answer in a table, and reads it back
4. How a piece's answer is built from the smaller answers beneath it

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Dynamic programming — solving a problem whose pieces overlap by solving each small piece once, storing its answer, and building the whole from the stored answers (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the waste it removes — solving the same piece twice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of building the table — smallest first in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the waste it removes — solving the same piece twice → the student studies the picture and names what each part shows
- GIF — a GIF of building the table — smallest first in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
