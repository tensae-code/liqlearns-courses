# Lesson plan — Nested Loops — and Converting Between Loop Structures

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Nested Loops — and Converting Between Loop Structures
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Loops inside loops, finding a set's minimum and maximum, and converting one repetition structure into another (Greece Grade 12, Anaptyxi Efarmogon study guide Ch.3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Nested loops and the min/max patterns** — A **nested loop (εμφωλευμένος βρόχος)** is a loop inside a loop: the inner loop runs **to its end for every single step** of the outer — the pattern of tables (a ΓΙΑ for rows holding a ΓΙΑ for columns) and of work over arrays of arrays. The same chapter works the standing **minimum/maximum patterns**: set the champion to the **first** value, then let every later value challenge it — the pattern whose classic fault is seeding the champion with 0 instead of the first value, a fault the guide names so it can be recognised in an exam script.
2. **Converting between loop structures** — ΓΛΩΣΣΑ's three structures — **ΟΣΟ…ΕΠΑΝΑΛΑΒΕ** (while), **ΑΡΧΗ_ΕΠΑΝΑΛΗΨΗΣ…ΜΕΧΡΙΣ_ΟΤΟΥ** (repeat-until) and **ΓΙΑ…ΑΠΟ…ΜΕΧΡΙ** (for) — can each be **converted** into the others: a ΓΙΑ becomes an ΟΣΟ with its counter handled openly; an ΟΣΟ becomes a ΜΕΧΡΙΣ_ΟΤΟΥ only with care, because ΜΕΧΡΙΣ_ΟΤΟΥ **always runs at least once** while ΟΣΟ may run **never**. The guide drills conversions because exams ask them directly — and because choosing the structure that *fits* a job, then proving the translation equal, is what mastery of repetition means.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A loop inside a loop — the inner runs to its end for every step of the outer
2. Tables — a ΓΙΑ for rows holding a ΓΙΑ for columns
3. The champion is set to the first value, then every later value challenges it
4. Seeding the champion with 0 instead of the first value

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The main book teaches ΓΛΩΣΣΑ's three loops. The study guide teaches the craft on top of them: nesting them, bending them to the min/max patterns, and translating a loop from one structure into another without changing what it does. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of nested loops and the min/max patterns as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of converting between loop structures in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of nested loops and the min/max patterns → the student studies the picture and names what each part shows
- GIF — a GIF of converting between loop structures in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
