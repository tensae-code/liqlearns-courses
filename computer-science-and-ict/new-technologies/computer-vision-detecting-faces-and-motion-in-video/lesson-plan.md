# Lesson plan — Computer Vision — Detecting Faces and Motion in Video

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Computer Vision — Detecting Faces and Motion in Video
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Kuwait's AI project experiments — detecting faces in images, and detecting motion in video, with OpenCV
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Face detection in images — the experiment's first form** — The first experiment is **detection** alone, practised as a skill: run the detector over **images** — class photos, portraits, crowds — and read its results honestly: faces found, faces missed (turned, shadowed, tiny), and false faces (patterns that are not people). Kuwait runs it as an experiment, with results recorded, because a detector's worth is not its best picture but its **rate** — and a pupil who has counted the misses understands every vision claim made to them afterwards.
2. **Motion detection in video — noticing change itself** — The second experiment turns to **video**: **motion detection** compares each frame with the one before, and where the picture has **changed enough**, reports **movement** — a person crossing, a door opening — without knowing what moved. It is vision at its most primitive and most useful: the camera that watches a corridor does not need to recognise anyone; it needs to know the corridor changed. The pair of experiments teaches the spectrum: detection names a thing, motion notices an event.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Face detection alone, over images — as a recorded experiment
2. Faces found, faces missed, and false faces
3. Its rate across many images — not its best picture
4. Each video frame with the one before

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Beyond the recogniser, Kuwait's AI project runs experiments: the same vision library turned on still images and then on moving ones. The second experiment is the stranger one — a program that notices movement itself. This lesson is the pair of experiments. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of face detection in images — the experiment's first form as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of motion detection in video — noticing change itself in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of face detection in images — the experiment's first form → the student studies the picture and names what each part shows
- GIF — a GIF of motion detection in video — noticing change itself in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
