# Lesson plan — Robot Gyroscope Sensor — Precise Turns and Proportional Control

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Robot Gyroscope Sensor — Precise Turns and Proportional Control
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The gyroscope sensor — turning to a target angle exactly — and proportional control: driving straight by correcting the error, with the constant Kp
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The gyroscope — knowing the robot's angle** — The **gyroscope sensor** measures the robot's **rotation**: how many degrees it has turned from where it started. With it, a turn stops being timed and hoped — the program turns **until the gyro reads the target angle**, then stops: 90 means 90, on any floor, with any battery. Precise turns are the first gift; the second is knowing the robot's heading at every moment, the fact straight driving needs.
2. **Proportional control — correcting by the error, with Kp** — Driving straight is a fight against drift, and **proportional control** is the fair way to fight it: measure the **error** — how far the heading is from the target — and correct **in proportion** to it: a big error, a strong correction; a small error, a gentle one. The proportion is set by the constant **Kp**: too small and the robot wanders; too large and it twitches. Tuning Kp — trying, watching, adjusting — is the engineer's real work, and Kuwait teaches it by name in Grade 8.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The robot's rotation — degrees turned from its start
2. The program turns until the gyro reads the target angle, then stops
3. 90 means 90 on any floor, with any battery — the turn is measured, not hoped
4. The robot's heading at every moment

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Counting motor turns makes sloppy corners. Grade 8's next sensor measures the turn itself. This lesson is the gyroscope — and the control idea that turns measurement into straight driving: proportional correction. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the gyroscope — knowing the robot's angle as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of proportional control — correcting by the error, with kp in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the gyroscope — knowing the robot's angle → the student studies the picture and names what each part shows
- GIF — a GIF of proportional control — correcting by the error, with kp in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
