# Lesson plan — A First C Program — Hello World and the main Function

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** A First C Program — Hello World and the main Function
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** a first C program: the shape every C program shares — header files, the main() function, and a first printed line — written and run in Code::Blocks as Bangladesh's HSC course begins its C teaching (Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The skeleton — headers and main** — A C program begins with **header lines** — `#include <stdio.h>` borrows the standard input-output library, the toolbox holding printf and scanf. Below it stands the **main() function**: `int main()` — the function the machine **starts at**, every time; a C program may hold many functions, but execution begins at main or nowhere. The function's body lives between **braces { }**, and each statement inside ends with a **semicolon** — C's full stop.
2. **Hello World — and running it in Code::Blocks** — The first program's whole work is one statement: `printf("Hello World");` — print the words between the quotes to the screen. The book writes and runs it in **Code::Blocks**, the free development environment of the HSC course: create the project, type the program exactly, **build** (the compiler translates it — the translator lesson at work), **run**, and read the greeting in the console window. When the greeting fails to appear, the compiler's error list is the first debugging text a C programmer learns to read: it names the line, and the fault is almost always a missing semicolon or brace — the skeleton's small bones, already teaching their importance.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The standard input-output library
2. printf and scanf
3. At the main() function
4. Braces { }

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every programming language has a first program, and by tradition it prints one greeting: Hello World. In C the greeting wears the language's whole skeleton — headers above, main in the middle, statements inside braces. Learn the skeleton once and every C program you ever meet is already half read. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the skeleton — headers and main as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of hello world — and running it in code::blocks in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the skeleton — headers and main → the student studies the picture and names what each part shows
- GIF — a GIF of hello world — and running it in code::blocks in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
