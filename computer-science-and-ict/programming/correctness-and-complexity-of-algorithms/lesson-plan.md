# Lesson plan — Correctness and Complexity of Algorithms

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Correctness and Complexity of Algorithms
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Judging an algorithm twice over: does it give the right answer (correctness), and what does it cost as the data grows (complexity) (Greece Grade 12, Anaptyxi Efarmogon Ch.5 and workbook)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Correctness — the right answer, for every honest input** — An algorithm is **correct** when, for **every** input its statement allows, it **ends** and gives the answer the problem asks for. The book tests correctness the working way: trace the algorithm on chosen inputs — the smallest, the largest, the awkward middle — and check each answer against the problem, because one honest counterexample is worth more than a hundred easy successes. The chapter works correctness beside its named kinds of algorithm, so 'correct' always means correct *for this problem's statement*, not correct in the air.
2. **Complexity — cost counted as growth** — **Complexity (πολυπλοκότητα)** counts an algorithm's cost — steps, and the memory it holds — **as the input size grows**, not in seconds on one machine. The chapter measures its standing examples against each other: the **straight-exchange sort** grows far faster than **linear search**, whose work simply follows the list's length; that growth shape is the judgement that survives every faster machine. The workbook's analysis chapter reworks correctness and complexity together as graded examples and activities.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. For every allowed input it ends and gives the answer the problem asks for
2. Trace it on chosen inputs — smallest, largest, awkward middle — and check each answer
3. One honest counterexample
4. Correct for this problem's statement

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — An algorithm can be fast and wrong, or right and hopeless. The exam course judges both faults separately — and this lesson is that double judgement. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of correctness — the right answer, for every honest input as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of complexity — cost counted as growth in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of correctness — the right answer, for every honest input → the student studies the picture and names what each part shows
- GIF — a GIF of complexity — cost counted as growth in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
