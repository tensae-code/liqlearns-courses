# Lesson plan — Binary — and How Integers Are Stored

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Binary — and How Integers Are Stored
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 10 Tin học 10), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the binary system and how integers are stored — counting in base two, and how a fixed row of bits holds whole numbers, including negative ones (Vietnam Grade 10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Binary — counting with two digits** — The **binary system** counts with two digits only, **0 and 1**, because a computer's memory is built of two-state switches. Place value still rules: each place is worth **twice** the place before it — 1, 2, 4, 8, 16 — so the binary number 1011 is 8 + 2 + 1 = **11** in decimal. Vietnam's Grade 10 data strand begins here, before sound and image data, because every kind of data the computer holds is, at the bottom, numbers written this way.
2. **Storing integers — a fixed row of bits, and the sign problem** — An integer is stored in a **fixed number of bits** — 8, 16, 32 or 64 — and the fixing decides the **range**: 8 bits hold 256 different values. Positive integers are stored as their binary value, padded with zeros. **Negative** integers need a scheme: the book's way is **two's complement** — invert the bits of the positive number and add 1 — which lets the same adder add and subtract, and gives one zero instead of two. The price of a fixed size is **overflow**: a result too big for the row of bits wraps or corrupts, and the program must care.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Only 0 and 1 — the two states of the computer's switches
2. Each place is worth twice the one before it — 1, 2, 4, 8, 16
3. 11 — that is 8 + 2 + 1
4. Because every kind of data the computer holds is, at the bottom, numbers written in binary

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — the binary system and how integers are stored — counting in base two, and how a fixed row of bits holds whole numbers, including negative ones (Vietnam Grade 10) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of binary — counting with two digits as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of storing integers — a fixed row of bits, and the sign problem in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of binary — counting with two digits → the student studies the picture and names what each part shows
- GIF — a GIF of storing integers — a fixed row of bits, and the sign problem in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
