# Lesson plan — Using a Standard Library

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Using a Standard Library
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** What a standard library is and how it is used — the ready-made collection that ships with the language (such as JavaScript's Math and Date), called instead of written (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The library — the language's ready-made shelves** — A **standard library** is the collection of **ready-made** functions and objects that **ships with the language itself** — no installing, no importing from strangers. In JavaScript the shelves this chapter uses include **Math** (Math.sqrt, Math.floor, Math.random, PI as Math.PI) and **Date** (the current date and time, and their parts). A library member is known by its **documentation**: what it takes, what it returns, what it promises — the programmer's job is to know the shelves and read the labels, not to rebuild the goods.
2. **Calling the library — trust, but verify the label** — Using the library is a **call**: name the member, hand it its values, take its return — let root = Math.sqrt(81); gives 9 without one line of root-finding written. Malaysia's disciplines of use are two: call the library **instead of hand-writing** what it already does correctly (a hand-written random or date routine is a fault waiting), and **check the label** before calling — Math.floor(3.9) gives 3, not 4, because floor promises the whole number **below**; most library 'faults' are labels misread. The standard library is the language's gift of other programmers' tested work; using it well is a form of reading.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The ready-made collection of functions and objects that ships with the language itself
2. No — it ships with the language
3. Math and Date
4. 9 — and no root-finding code at all

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — No programmer writes their own square root twice. Every serious language ships with a standard library — Malaysia's scripting chapter teaches its use as a skill. In this lesson you learn what the library holds, and how a program calls on it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the library — the language's ready-made shelves as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of calling the library — trust, but verify the label in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the library — the language's ready-made shelves → the student studies the picture and names what each part shows
- GIF — a GIF of calling the library — trust, but verify the label in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
