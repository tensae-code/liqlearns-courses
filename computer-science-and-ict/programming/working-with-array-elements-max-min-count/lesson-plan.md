# Lesson plan — Working with Array Elements — Operations, Largest, Smallest, Counting

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Working with Array Elements — Operations, Largest, Smallest, Counting
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** The basic array operations all share one walk: keep a running answer outside the loop (a total, the largest so far, a count), visit every element once, and update the answer by comparing or adding — largest starts from the first element, counting tests each element against a condition, and the walk itself never changes the array.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Operations over the whole array** — The pattern: an **accumulator** starts at its neutral value (0 for a sum), the loop visits **every** element, and each visit **folds** the element in — total += a[i]. The same walk with a different fold gives products, sums of squares, or a transformed second array (each element doubled, say). The array itself is only read, never changed, in this family of tasks.
2. **Largest, smallest and counting** — For **largest**: set max = **a[0]** (never 0 — an all-negative array would break that), then each element that **beats** max replaces it. **Smallest** mirrors it. For **counting**: a counter rises by one **only when the element passes a test** (negative? even? above the average?) — same walk, conditional fold. The links-pass reading splits this material further: inserting elements, finding largest/smallest and counting each get their own stocked lessons beside this one.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A running answer — the accumulator.
2. total += a[i].
3. The first element, a[0].
4. The counter rises only when the element passes a test.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Almost every array job is the same walk wearing different clothes. This lesson teaches the walk once, in its three classic outfits: total and operations, largest-and-smallest, and counting. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of operations over the whole array as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of largest, smallest and counting in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of operations over the whole array → the student studies the picture and names what each part shows
- GIF — a GIF of largest, smallest and counting in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
