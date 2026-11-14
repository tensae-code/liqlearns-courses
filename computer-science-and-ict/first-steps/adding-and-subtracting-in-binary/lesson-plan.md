# Lesson plan — Adding and Subtracting in Binary

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Adding and Subtracting in Binary
**Place in the curriculum:** ICT expansion — Yemen (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Yemen's *Computer* Grade 11, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Binary arithmetic follows the same column rules as decimal, with a smaller digit set: adding works with carries when 1 + 1 makes 10 in binary, and subtracting works with borrows when a 0 must take from the column beside it.
**This lesson's own level:** It stands on the earlier lessons of its title and on the Yemen book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Adding in binary — carry the two** — Add column by column from the right, exactly as in decimal. The only sums are: 0 + 0 = **0**, 0 + 1 = **1**, and 1 + 1 = **10 in binary** — write **0** and **carry 1** into the next column, just as 5 + 5 carries in decimal. Where a carry arrives, add three digits: 1 + 1 + 1 = **11 in binary** — write 1, carry 1. Example: 101 + 11 = 1000 (5 + 3 = 8 — check it in decimal).
2. **Subtracting in binary — borrow a two** — Subtract column by column from the right: 0 − 0 = **0**, 1 − 0 = **1**, 1 − 1 = **0**. The hard case is 0 − 1: **borrow** from the next column — the borrowed 1 is worth **2** in your column (a whole place), so 2 − 1 = **1**, and the lending column drops by one. Example: 101 − 11 = 10 (5 − 3 = 2). Again the decimal check proves the binary work.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Yemen's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. At the right-hand column, as in decimal.
2. 10 — write 0 and carry 1.
3. 0.
4. Borrow from the next column.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — You can already add in decimal by columns, carrying when a column overflows. Binary asks for the same skill with only 0 and 1. In this lesson you add and subtract in binary, column by column. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a binary addition worked in columns, with the carry marked — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of a binary subtraction with the borrow marked over the lending column — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a binary addition worked in columns, with the carry marked → the student studies the picture and names what each part shows
- GIF — a GIF of a binary subtraction with the borrow marked over the lending column → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
