# Lesson plan — Translating an Algorithm into Code

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Translating an Algorithm into Code
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How an algorithm is translated into a programming language — structure by structure, pseudocode or flowchart into Java, without changing what the algorithm does (Malaysia, Tingkatan 4)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Structure by structure** — Translation works **structure by structure**, not line by wandering line: a pseudocode **sequence** becomes statements in the same order; a **selection** (IF…THEN…ELSE) becomes Java's if…else with its condition in brackets and its branches in braces; a **repetition** (WHILE or FOR) becomes Java's while or for. Variables in the algorithm are declared in the code before their first use, with the types the algorithm's values need. The flowchart translates the same way — each box and diamond has its code shape, and the arrows become the code's order and nesting.
2. **What translation must never change** — Translation changes the **language**, never the **logic**: the translated program must do **exactly** what the algorithm does — same steps, same tests, same order. Malaysia's check is a **parallel trace**: run one set of test values through the algorithm by hand and through the program, and the two must agree at every step. A disagreement is a translation fault — a dropped branch, a swapped comparison, a loop test turned upside down — and it is repaired in the code, against the algorithm, which remains the authority. Code written without an algorithm to answer to cannot be checked this way, which is why this course never writes it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Structure by structure — not line by wandering line
2. Statements in the same order
3. if…else — the condition in brackets, the branches in braces
4. The logic — same steps, same tests, same order

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The algorithm is finished on paper. Now it must live in Java — saying exactly the same thing in a stricter tongue. Malaysia's programming chapter teaches translation as its own step. In this lesson you translate, structure by structure, and learn what translation must never change. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of structure by structure as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of what translation must never change in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of structure by structure → the student studies the picture and names what each part shows
- GIF — a GIF of what translation must never change in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
