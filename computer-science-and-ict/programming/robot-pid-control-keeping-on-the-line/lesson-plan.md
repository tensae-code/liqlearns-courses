# Lesson plan — Robot PID Control — Keeping on the Line

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Robot PID Control — Keeping on the Line
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The PID control system — proportional, integral and derivative — correcting a line-following robot's drift
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Three corrections — P, I and D** — **PID** names three corrections added together. **Proportional (P)** corrects by the error **now** — the Grade 8 teaching. **Integral (I)** corrects by the error **accumulated**: a drift that leans the same way for a long time is summed, and the sum pushes back, ending the lean a merely present correction tolerates. **Derivative (D)** corrects by the error's **rate of change**: a fast-growing error is met early, before it becomes a swerve. Now, accumulated, and coming — the three tenses of error.
2. **PID on the line** — On the line, the error is the reflected-light reading's distance from the line's edge value, read many times a second. P alone wanders around the edge; I removes the stubborn offset of a curved or tilted run; D damps the zigzag that eager correction causes. Tuning three constants instead of one is harder and is the point: the Grade 9 robot is kept on its line by the same controller family that keeps real machines on theirs — Kuwait's robotics strand arriving at genuine control theory.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Proportional, Integral, Derivative
2. The error now
3. The accumulated error over time — ending a long lean
4. The error's rate of change — meeting a fast-growing error early

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 8 corrected drift in proportion to the error. Grade 9 completes the controller: three corrections together, each answering a different failure of the simple one. This lesson is PID — the robot engineer's standard answer to staying on a line. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of three corrections — p, i and d as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of pid on the line in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of three corrections — p, i and d → the student studies the picture and names what each part shows
- GIF — a GIF of pid on the line in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
