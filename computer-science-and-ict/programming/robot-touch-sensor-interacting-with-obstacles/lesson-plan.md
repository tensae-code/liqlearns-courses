# Lesson plan — Robot Touch Sensor — Interacting with Obstacles

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Robot Touch Sensor — Interacting with Obstacles
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The Touch sensor on the SPIKE robot in Open Roberta Lab's RCJ Rescue simulation — a robot that feels obstacles, in the parking and robot-returns-home missions
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The Touch sensor — the robot feels what it meets** — The **Touch sensor** is a button on the robot's front that is **pressed when the robot meets an obstacle**: the program can ask it at any moment — pressed or not — and branch on the answer. With touch, the robot's world stops being only the plan in its program: the wall announces itself by being touched, and 'drive until you feel it' becomes a writable instruction — the first sensing loop of the series.
2. **Missions — parking, and the robot returns home** — The book's missions spend the new sense at once. In **parking**, the robot drives into its bay until touch says the bay's end is reached — stopping by evidence, not by a guessed distance. In **robot returns home**, touch marks the journey's landmarks: each meeting with an obstacle is information the program uses to find its way back. Both missions run in the **RCJ Rescue simulation** in Open Roberta Lab, on the SPIKE robot — competition ground, in the classroom.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A front button pressed when the robot meets an obstacle — the program can ask: pressed or not
2. 'Drive until you feel it' — the first sensing loop
3. By being touched
4. By evidence — touch at the bay's end — not by a guessed distance

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A robot that cannot feel the wall drives into it. Grade 7's robotics unit gives the virtual robot its first true sense: touch. This lesson is the Touch sensor — what it feels, and the missions it makes possible. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the touch sensor — the robot feels what it meets as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of missions — parking, and the robot returns home in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the touch sensor — the robot feels what it meets → the student studies the picture and names what each part shows
- GIF — a GIF of missions — parking, and the robot returns home in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
