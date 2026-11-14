# Lesson plan — How Data Is Encoded — Text, Sound and Images

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** How Data Is Encoded — Text, Sound and Images
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Encoding is the agreed code that turns each kind of thing into numbers: every character gets a code number (as in ASCII), a sound is sampled — measured thousands of times a second — and each measurement stored, and an image is split into pixels whose colours are stored as numbers; decoding runs the same code backwards.
**This lesson's own level:** It stands on the digitisation lesson: digitisation says the world becomes binary data; this lesson shows the actual codes that do it, kind by kind. It pairs with the number-systems lesson — codes are written in binary.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Encoding text — every character a number** — Text is the simplest code. The characters a language uses are listed in an agreed table, and each character is given a number: in the **ASCII** code, capital A is 65, B is 66, the digit 5 is 53 — and the computer stores the number, in binary, wherever the character appears. Wider tables such as Unicode extend the same idea to the characters of all the world's scripts, including Chinese characters, so any text in any language becomes numbers by one rule: *look the character up, store its number; look the number up, get the character back.* Encoding and decoding are the same table read in opposite directions.
2. **Encoding sound and images — sampling and pixels** — A sound is continuous, so it cannot be looked up — it must be **sampled**: the wave's height is measured at regular moments, thousands of times per second, and each measurement is stored as a number. Played back, the numbers rebuild a wave so close to the original that the ear accepts it; more samples per second and finer measurements mean a closer copy and a bigger file. An image is split instead of timed: it is cut into a grid of tiny dots, **pixels**, and each pixel's colour is stored as numbers (for example, amounts of red, green and blue). More pixels mean a sharper picture and, again, a bigger file. Quality against size is the trade every encoding makes.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Say how text is encoded, using a code table such as ASCII, and decode a number back to its character.
2. Say how sound is encoded by sampling, and what more samples per second changes.
3. Say how an image is encoded with pixels and colour numbers.
4. State the trade every encoding makes: more detail (quality) against bigger file size.

## What you need
Paper, a pencil, and squared (grid) paper for the hands-on.

## The run of the lesson (in order)
1. **Do it first** — Hold three things in your mind: the letter A, one second of a sung note, and a photograph of your face. The computer stores all three as nothing but numbers — but not by the same trick. Each kind has its own code. This lesson opens all three codes and looks inside. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a code table like a bus timetable — letters down the side, numbers beside them — with the letter A highlighted beside its number 65, and 65 rewritten in binary beside it — the student finds two more characters in the table and reads off their numbers.
   - ADD GIF: a GIF of a sound wave being measured by a row of vertical lines rising one after another, each turning into a number — then the same numbers growing back into the wave — the student watches once, then says what more samples per second would do to the copy and to the file.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a code table like a bus timetable — letters down the side, numbers beside them — with the letter A highlighted beside its number 65, and 65 rewritten in binary beside it → the student finds two more characters in the table and reads off their numbers
- GIF — a GIF of a sound wave being measured by a row of vertical lines rising one after another, each turning into a number — then the same numbers growing back into the wave → the student watches once, then says what more samples per second would do to the copy and to the file
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks the computer stores tiny letters and tiny pictures → it stores numbers only; the code table and the pixel grid are what turn numbers back into letters and pictures. Confuses sampling with pixels → sampling cuts sound through time; pixels cut an image through space. Both turn the continuous into countable pieces.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
