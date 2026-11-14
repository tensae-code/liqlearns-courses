# Lesson plan — Working with Raster Images in PascalABC

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Working with Raster Images in PascalABC
**Place in the curriculum:** ICT expansion — Belarus (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Belarus's *Інфарматыка* Grade 11, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A raster image — a picture stored as a grid of pixels, loaded from a file — can be placed, moved and animated by a PascalABC program: the program redraws it at new coordinates step by step, and the steps become motion.
**This lesson's own level:** It stands on the earlier lessons of its title and on the Belarus book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Raster images in a program** — A **raster image** is a picture made of a grid of coloured points (**pixels**) — the kind of picture a photograph or a saved drawing is. Unlike a figure the program draws from commands, a raster image is **loaded from a picture file** and placed on the graphics window at chosen coordinates, whole, as one object. The program can draw it again elsewhere, cover it, or layer figures over it. Its size in pixels is its size on the window: a big picture file covers a big area, whatever it shows.
2. **Moving and animating** — **Animation** here is movement built from still steps: draw the image, wait a blink, clear or cover its old place, and draw it at the next coordinates — repeated quickly, the eye joins the steps into **motion**. Direction and speed are just the step pattern: how far the coordinates change each step, and how long the pause is. The craft problems are the visible ones — a trail left behind when the old position is not cleaned, jerky steps when the jumps are too big — and each is fixed in the step pattern, not in the picture.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Belarus's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A picture made of a grid of coloured points — pixels.
2. A figure is built from drawing commands; a raster image is loaded ready-made.
3. The step pattern — how far coordinates change each step, and the pause length.
4. Its size in pixels.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Your drawn figures can move — but so can a whole photograph. In this lesson a PascalABC program loads a raster picture and walks it across the window, step by step, until still pictures become animation. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a photograph as a grid of pixels being lifted whole onto a graphics window — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the same picture drawn at five positions across a window with arrows between them, joining into motion — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a photograph as a grid of pixels being lifted whole onto a graphics window → the student studies the picture and names what each part shows
- GIF — a GIF of the same picture drawn at five positions across a window with arrows between them, joining into motion → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
