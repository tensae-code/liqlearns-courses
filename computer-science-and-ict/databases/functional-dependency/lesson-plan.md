# Lesson plan — Functional Dependency

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Functional Dependency
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** What functional dependency means — attribute B depends on attribute A when A's value settles B's value — and how dependencies are found and written (A → B) before normalisation (Malaysia, Tingkatan 4)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The arrow — A settles B** — Attribute **B functionally depends on A** — written **A → B** — when each value of A is always paired with **exactly one** value of B: knowing A settles B. A pupil's ID settles her name (PupilID → PupilName): two records with the same ID cannot carry two different names. But PupilName does not settle PupilID — two pupils can share a name. Dependency is **one-directional** and it is a claim about the **meaning** of the data, not about the records that happen to be present today.
2. **Finding and using dependencies** — Dependencies are **found** by testing pairs with the meaning test: 'if I know this, do I always know that?' — checked against the world's rules (an ISBN settles a book's title; a book's title settles nothing). A table's dependencies are listed in full before normalisation begins, because normalisation is nothing but acting on them: where a non-key attribute depends on **part** of a key, or on **another non-key attribute**, the design carries a fault the dependencies have already named. The arrow list is the diagnosis; normalisation is the cure.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. B functionally depends on A — each value of A is paired with exactly one value of B
2. Knowing A settles B
3. No — two pupils can share a name; dependency is one-directional
4. By the meaning test: 'if I know this, do I always know that?'

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Normalisation has a tool, and this is it. Malaysia teaches functional dependency first: a way of saying, exactly, which values settle which other values in a table. In this lesson you learn to find dependencies and write them with the arrow. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the arrow — a settles b as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of finding and using dependencies in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the arrow — a settles b → the student studies the picture and names what each part shows
- GIF — a GIF of finding and using dependencies in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
