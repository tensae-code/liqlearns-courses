# Lesson plan — Converting Binary to Octal

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Converting Binary to Octal
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to convert a binary number to octal by grouping the bits in threes from the right and reading each group as one octal digit
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Group in threes — from the right** — Starting at the **right-hand end** of the binary number, split the bits into **groups of three**. Grouping must start from the right because the places run from the right; grouping from the left would misplace every value. If the last group on the left has only one or two bits, it still counts as a group — think of it as filled with leading zeros (10 is 010) without changing the number's value.
2. **Each group — one octal digit** — Read **each group as one octal digit** (000→0 up to 111→7) and write the digits in order: 100111₂ → groups 100 | 111 → 4, 7 → **47₈**. The binary number 101010₂ → 101 | 010 → **52₈**. Malaysia teaches the two directions together: octal-to-binary spreads each digit into three bits; binary-to-octal gathers three bits into each digit — inverse roads over the same kinship.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. In threes
2. From the right — the places run from the right
3. Grouping from the left would misplace every value
4. 47₈ — groups 100 and 111

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A long binary number is heavy to read. Group its bits in threes and it shortens into octal — the return road of the last conversion. In this lesson you group from the right and read each group as a single digit. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of group in threes — from the right as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of each group — one octal digit in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of group in threes — from the right → the student studies the picture and names what each part shows
- GIF — a GIF of each group — one octal digit in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
