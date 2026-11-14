# Lesson plan — Swapping Two Values — and Reversing an Array

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Swapping Two Values — and Reversing an Array
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** swapping two values with a temporary variable — and spending the swap on its classic errand, reversing an array in place (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The swap — three moves with a temporary** — To **swap** the values of a and b, a third variable holds one of them safe: `temp = a; a = b; b = temp;` — **three moves**, in that order, and no other order works. The beginner's two-move version, `a = b; b = a;`, loses a's value at the first move: b's value overwrites it before it is saved, and both variables end holding b's old value. The temporary variable is the third glass — small, unglamorous, and the difference between exchange and loss. Every sort, shuffle and reversal in programming is built from this one honest move.
2. **Reversing an array — swaps walking to the middle** — To **reverse an array** in place: swap the **first with the last**, the **second with the second-last**, walking inward until the two walkers **meet in the middle** — for an odd length, the middle element stays, already home. Five elements take two swaps; a hundred take fifty — always **half the size**, rounded down. The loop's indices are the craft: i climbs from the start while j descends from the end, and the loop stops when i is no longer less than j. Reverse is the swap's portrait as the calculator was assembly's: a tiny algorithm whose correctness can be seen whole, and whose off-by-one faults teach the array lesson's edge discipline better than any warning.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Three
2. temp = a; a = b; b = temp;
3. a's value is overwritten before it is saved
4. The third glass

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Two glasses, one full of water, one of juice. Exchange their contents without mixing them and you will invent this lesson in your hands: you reach for a third glass. Programs swap values constantly — sorting is swapping with ambition — and they reach for the same third glass. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the swap — three moves with a temporary as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of reversing an array — swaps walking to the middle in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the swap — three moves with a temporary → the student studies the picture and names what each part shows
- GIF — a GIF of reversing an array — swaps walking to the middle in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
