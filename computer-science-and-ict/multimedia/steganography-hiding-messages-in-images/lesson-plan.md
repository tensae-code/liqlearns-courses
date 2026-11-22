# Lesson plan — Steganography — Hiding Messages in Images

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Steganography — Hiding Messages in Images
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Steganography hides a message inside an ordinary-looking file: in an image, the last bit of each colour number can be replaced by a bit of the message — the pixel changes by at most one, the eye sees nothing, and a program that knows the scheme can read the message back out.
**This lesson's own level:** It stands on binary (each colour number is bits), on pixels and RGB, and on the PIL lesson — the hiding is done by the same pixel-walking program. A learner who has built a filter can start here.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Hiding bits in the least significant bits** — Each colour value is a byte; its last bit — the least significant bit — changes the value by at most 1. Replacing that bit with a message bit alters the image invisibly; a row of pixels then carries a row of message bits, which the receiver collects in the agreed order.
2. **Coding and decoding a hidden message** — Turning letters into bits (the book uses a 6-bit base-64 code), writing them into the LSBs of the RGB values with a PIL program, and the mirror program that reads the LSBs back and rebuilds the message — plus the limits: the image must not be re-compressed, and hiding is not encrypting.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Multimedia lesson on programming image filters with PIL and the Programming lessons on binary, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "La photographie numérique", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Explain what the least significant bit of a colour value is and why changing it cannot be seen.
2. Turn a short message into bits with a 6-bit code and say how many hiding places each letter needs.
3. Describe the coding program and the decoding program, step by step.
4. State why the carrier image must be saved as PNG rather than JPEG, and why hiding is not the same as encrypting.

## What you need
A computer with Python and Pillow for the coding work; the scheme itself can be worked on paper with a tiny image.

## The run of the lesson (in order)
1. **Do it first** — Look at two nearly identical colour numbers — 200 and 201 — and judge whether anyone could see the difference on screen, before the lesson uses that invisibility. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one colour byte as eight bit boxes, the last box highlighted being swapped for a message bit — the student reads the byte before and after the swap and says how much the value moved
   - ADD GIF: a GIF of a sentence turning into 6-bit codes, then into a photo that looks unchanged, then back into the sentence — the student pauses the GIF at the photo and says where the message is at that moment
   - ADD IMAGE: a picture of the round trip drawn as a circle — sentence, codes, photo, sentence — the student walks the circle aloud, naming the program that performs each step
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one colour byte as eight bit boxes, the last box highlighted being swapped for a message bit → the student reads the byte before and after the swap and says how much the value moved
- GIF — a GIF of a sentence turning into 6-bit codes, then into a photo that looks unchanged, then back into the sentence → the student pauses the GIF at the photo and says where the message is at that moment
- IMAGE — a picture of the round trip drawn as a circle — sentence, codes, photo, sentence → the student walks the circle aloud, naming the program that performs each step
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Changes the wrong bit → the hiding place is the LAST bit of the byte (the 1s place); changing any other bit moves the value visibly. Message decodes as garbage → the two programs must walk the pixels in exactly the same order and group the bits the same way (six per letter). Carrier saved as JPEG → JPEG compression rewrites colour values and destroys LSBs; the carrier must stay PNG.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches steganography in the En codant strand of its photography theme, with a base-64 code on 6 bits — this lesson follows that scheme exactly.
