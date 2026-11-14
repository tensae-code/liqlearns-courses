# Lesson plan — Converting Decimal to Octal

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Converting Decimal to Octal
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to convert a decimal number to octal by dividing by 8 again and again and reading the remainders upwards
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Divide by 8, keep the remainders** — Write the decimal number and **divide it by 8**. Write the **remainder** — always a digit from 0 to 7 — to the side. Divide the new answer by 8 again, and keep going until the answer reaches **0**. For 25: 25 ÷ 8 = 3 rem **1**; 3 ÷ 8 = 0 rem **3**. The divisions are finished; the remainders, in order, are 1, 3 — but they are not yet the answer in that order.
2. **Read the remainders upwards — and check** — The octal number is the remainders read **from last to first** — upwards: for 25, that gives **31₈**. The first remainder you found is the **last** digit of the octal number, its ones place; the last remainder is its first digit, the biggest place. Check by place value: 31₈ = 3×8 + 1 = 25. If the check fails, a division or the reading direction went wrong — the check is part of the method, not an extra.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. By 8 — the octal base
2. The remainder — always a digit from 0 to 7
3. When the answer reaches 0
4. 31₈

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A decimal number must sometimes be written the octal way. Malaysia's Grade 8 book gives one method that always works: divide by eight, keep the remainders, read them upwards. In this lesson you work that method until it is yours. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of divide by 8, keep the remainders as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of read the remainders upwards — and check in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of divide by 8, keep the remainders → the student studies the picture and names what each part shows
- GIF — a GIF of read the remainders upwards — and check in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
