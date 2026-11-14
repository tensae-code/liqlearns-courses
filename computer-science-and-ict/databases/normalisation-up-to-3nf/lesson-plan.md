# Lesson plan — Normalisation up to 3NF

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Normalisation up to 3NF
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How unnormalised data is normalised step by step — 0NF to 1NF (atomic values, no repeating groups), 2NF (no partial dependency), 3NF (no transitive dependency) — Malaysia's school-level normalisation, taught in Tingkatan 4 and again in Tingkatan 5
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **0NF to 1NF — atomic values, one fact per cell** — Data in **0NF** (unnormalised) may hold **repeating groups**: a pupil record listing Subject1, Subject2, Subject3, or one cell holding 'Maths, English' together. **First normal form (1NF)** requires **atomic values** — each cell holds **one** fact, never a list — and the repeating group is removed by giving each repeated fact **its own record** (one record per pupil–subject pair), with a key that identifies every record. 1NF's gain is addressability: every fact can now be found, counted and updated on its own.
2. **2NF and 3NF — dependencies put in their own tables** — **Second normal form (2NF)** acts when the key is **composite**: every non-key attribute must depend on the **whole key**, not on **part** of it (a pupil's name depends only on PupilID, not on the PupilID+Subject pair — so names leave the enrolment table for the pupil table). **Third normal form (3NF)** removes **transitive dependency**: a non-key attribute must not depend on **another non-key attribute** (a teacher's room depends on the teacher, not on the pupil — so it leaves for the teacher table). At 3NF each fact lives in exactly one table, updates touch one place, and the design is what Malaysia calls ternormal — normalised.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Repeating groups — Subject1, Subject2, Subject3, or several facts in one cell
2. Atomic values — one fact per cell — and a key identifying every record
3. Each repeated fact gets its own record — one record per pupil–subject pair
4. Every non-key attribute depends on the whole key, not part of it

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — One big table with everything in it is where database trouble lives: repeated groups, half-known facts, updates that miss copies. Malaysia teaches the cure as a staircase of normal forms. In this lesson you climb 0NF to 3NF, one fault removed per step. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of 0nf to 1nf — atomic values, one fact per cell as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of 2nf and 3nf — dependencies put in their own tables in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of 0nf to 1nf — atomic values, one fact per cell → the student studies the picture and names what each part shows
- GIF — a GIF of 2nf and 3nf — dependencies put in their own tables in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
