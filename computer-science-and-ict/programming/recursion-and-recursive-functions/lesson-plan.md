# Lesson plan — Recursion and Recursive Functions in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Recursion and Recursive Functions in Python
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** recursion in Python — a function that calls itself, its base case, and how the calls unwind (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What recursion is — the two parts** — A **recursive function** solves a problem by calling **itself on a smaller piece** of it. Every working recursion has two parts: the **base case** — the smallest piece, answered directly, where the calls stop — and the **recursive case** — the answer for the whole built from the answer for the smaller piece. Factorial is the book's standing example: n! = n × (n−1)!, with 0! = 1 as the base — the definition and the program have the same shape, which is recursion's beauty and its danger.
2. **How the calls unwind — and the faults** — Each call **waits** on the call-stack for its smaller call's answer; when the base case answers, the stack **unwinds**, each waiting call completing in turn. The faults are the two missing guards: **no base case** (or one never reached) — calls without end, until Python stops the program with a recursion error; and a recursive step that does not **shrink** the problem — the same endlessness by another road. Jordan teaches recursion after the data structures because its finest work is on them: trees and nested lists are smaller-piece-shaped by nature.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Itself, on a smaller piece of the problem
2. The base case and the recursive case
3. The smallest piece, answered directly, where calls stop
4. n! = n × (n−1)!; base 0! = 1

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A function that calls itself sounds like a dog chasing its tail. With one guard — a case where it stops — it becomes one of programming's most elegant tools. This lesson learns the guard and the chase. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of what recursion is — the two parts as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of how the calls unwind — and the faults in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of what recursion is — the two parts → the student studies the picture and names what each part shows
- GIF — a GIF of how the calls unwind — and the faults in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
