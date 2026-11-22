# Lesson plan — Programming Image Filters with Python PIL

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Programming Image Filters with Python PIL
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** With Python’s Pillow library (PIL), a program can open an image, visit every pixel, read its RGB numbers, and write new numbers back — and that single ability is enough to build real filters: greyscale, negative, darkening, and any effect that is a rule applied pixel by pixel.
**This lesson's own level:** It stands on the image-coding lessons (a pixel is three numbers) and on Python loops. A learner who can write a for loop and knows RGB can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Opening an image and reaching its pixels** — Pillow opens an image file into an image object with a size and a mode; the program can then load its pixels, read the RGB triple at any (x, y) position, and write a new triple back — the image as a grid of numbers the program can touch.
2. **Building filters pixel by pixel** — A filter is a rule plus two loops: for every pixel, compute the new triple from the old — greyscale by averaging, negative by subtracting from 255, brightness by scaling — then save the result as a new image, keeping the original untouched.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Multimedia lesson on pixels and colour depth and the Programming lessons on Python loops, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "La photographie numérique", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Open an image with Pillow and state its size and mode.
2. Read the RGB triple at a chosen (x, y) position and write a new triple there.
3. Write the two loops that visit every pixel of an image.
4. Build and run a greyscale filter and a negative filter, saving each result under a new name.

## What you need
A computer with Python and the Pillow library for the coding work. The first part — inventing rules on a tiny grid — needs only paper.

## The run of the lesson (in order)
1. **Do it first** — Take a tiny 3×3 image as a grid of RGB triples and apply a "make it grey" rule by hand — before the lesson shows the program that does it to millions of pixels. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a photo beside a magnified corner where pixels show as a grid of RGB triples, one cell highlighted at its (x, y) address — the student reads the triple at the highlighted address and says its row and column
   - ADD GIF: a GIF of a scan line sweeping a photo top to bottom, the photo turning grey behind the line — the student says which loop is moving as the line descends, and which as it crosses
   - ADD IMAGE: a picture of one photo shown four times — original, greyscale, negative, threshold — with the rule under each — the student matches a fifth triple, worked by hand, to the filter that produced it
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a photo beside a magnified corner where pixels show as a grid of RGB triples, one cell highlighted at its (x, y) address → the student reads the triple at the highlighted address and says its row and column
- GIF — a GIF of a scan line sweeping a photo top to bottom, the photo turning grey behind the line → the student says which loop is moving as the line descends, and which as it crosses
- IMAGE — a picture of one photo shown four times — original, greyscale, negative, threshold — with the rule under each → the student matches a fifth triple, worked by hand, to the filter that produced it
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Loops visit only part of the image → the loop limits are the image’s width and height, read from the image itself, not typed from memory. Colours come out wrong → check the mode: a greyscale or palette image does not hand back RGB triples until it is converted. Overwrote the original photo → the book’s rule: open, work, save under a new name; recover this once from a copy, then keep the rule.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches this in the En codant strand of its photography theme — real filters on real photos with PIL; this lesson follows that strand’s order: open, reach the pixels, then build filters.
