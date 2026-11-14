# Lesson plan — Computer Vision — Face Recognition with OpenCV

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Computer Vision — Face Recognition with OpenCV
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Kuwait's AI project in code — recognising faces in images with Python's OpenCV library
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **OpenCV — Python's eyes** — **OpenCV** is a **library** — ready-made code a Python program imports — for working with images and video: reading a picture into the program, processing its pixels, and detecting the patterns vision is made of. Kuwait's AI projects import it as the modules lesson taught: someone else's solved problems, called by name. The face project is the import with a face: `import cv2`, and the program can suddenly work on photographs, not just numbers the user types.
2. **Recognising a face — from pixels to a person** — The project's program runs the vision pipeline: **load** the image, **detect** the faces in it (the Haar-cascade craft the database project also uses — rectangles drawn where faces are), then **recognise** — compare a detected face against the faces the program knows, and name the match or honestly report a stranger. Kuwait teaches the honesty as part of the build: a recogniser that guesses a name for every face is worse than one that says 'unknown', because the project's output will be believed and acted on.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A library — ready-made code imported into Python — for images and video
2. As cv2 — `import cv2`
3. Photographs — not just typed numbers
4. Load the image, detect faces, recognise (compare and name)

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The Grade 10 AI unit ends in a project that makes the computer see: a Python program that finds and recognises faces, built on the OpenCV library. This lesson is that project's core — the library and the seeing. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of opencv — python's eyes as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of recognising a face — from pixels to a person in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of opencv — python's eyes → the student studies the picture and names what each part shows
- GIF — a GIF of recognising a face — from pixels to a person in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
