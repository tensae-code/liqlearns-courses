# Lesson plan — Bubble Sort

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Bubble Sort
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How bubble sort works — passing through the list swapping neighbouring pairs that are out of order, so the biggest unsorted value bubbles to the end on every pass (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Neighbours compared, neighbours swapped** — **Bubble sort** works in **passes** through the list. On each pass, every **neighbouring pair** is compared from the start; if the pair is **out of order** (the left bigger than the right, for ascending order), the two are **swapped**; if in order, they are left. One pass does not finish the sort — it guarantees one thing: the **biggest** of the unsorted values has been swapped step by step to the **end**, like a bubble rising — the movement that names the method.
2. **Pass after pass, until a clean pass** — The passes repeat over the **still-unsorted front** of the list — the sorted tail at the end is left alone. Each pass parks one more biggest value, so the passes get shorter. The sort is finished when a **whole pass makes no swaps** — every neighbour already in order means the list is sorted. Malaysia's pseudocode nests the shape: an outer loop for passes, an inner loop for the neighbour comparisons, and a swapped flag to catch the clean pass. Bubble sort is simple and slow — its teaching worth is that every swap can be watched and counted.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Neighbouring pairs, from the start of the list
2. When they are out of order — the left bigger than the right, for ascending order
3. The biggest unsorted value has reached the end
4. Each pass parks one more biggest value at the end

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Watch a list being sorted by neighbours alone: compare two side by side, swap them if they are in the wrong order, step on. Malaysia's first sort is bubble sort. In this lesson you bubble a list into order, pass by pass. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of neighbours compared, neighbours swapped as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of pass after pass, until a clean pass in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of neighbours compared, neighbours swapped → the student studies the picture and names what each part shows
- GIF — a GIF of pass after pass, until a clean pass in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
