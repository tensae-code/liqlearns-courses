# Lesson plan — Built-In Functions in BASIC — SQR, SIN, LEFT$ and LEN

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Built-In Functions in BASIC — SQR, SIN, LEFT$ and LEN
**Place in the curriculum:** ICT expansion — Sudan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Sudan's Grade 11 Computer Science student book, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** BASIC carries a toolbox of built-in (reserved) functions: named pieces of work the language itself performs. The second family works on strings — text held in string variables.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Built-in functions — work the language does for you** — BASIC carries a toolbox of **built-in (reserved) functions**: named pieces of work the language itself performs. You give a function a value and it hands back a result — no program of yours defines how. The mathematical family comes first in Sudan's book: **SQR** gives a number's square root, **SIN** its sine, and their fellows give cosines, tangents, absolute values and whole parts. Writing `LET R = SQR(81)` stores 9 — the root was found by the language, not by your lines.
2. **String functions — LEFT$ and LEN** — The second family works on **strings** — text held in string variables. **LEN** counts a string's characters: `LEN("KHARTOUM")` is 8. **LEFT$** cuts from the left: `LEFT$("KHARTOUM", 4)` is "KHAR" — the first four characters. Their partners cut from the right and the middle. A built-in function is recognised the same way in both families: a reserved name, a value in brackets, a single result out. The next lesson turns the idea around — functions the programmer defines for herself.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Sudan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A named piece of work the language itself performs — you give a value, it hands back a result.
2. 9 — the square root of 81.
3. 8 — the count of the string's characters.
4. A reserved name, a value in brackets, a single result out.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Find the square root of 81 by hand — then imagine a program that must do it a thousand times. BASIC refuses to make you write that work: it is already written, inside the language, waiting for its name. This lesson opens the toolbox. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of built-in functions — work the language does for you as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of string functions — left$ and len in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of built-in functions — work the language does for you → the student studies the picture and names what each part shows
- GIF — a GIF of string functions — left$ and len in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
