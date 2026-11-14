# Lesson plan — Compiler Directives in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Compiler Directives in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Compiler directives: instructions not to the running program but to the compiler — switching checks in Pascal ({$R+} and kin), and in C++ the preprocessor's #include, #define and #ifdef that work before compilation proper (Moldova Grade 10, Informatică, §1.5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Directives — orders to the builder** — A **compiler directive** is an instruction **to the compiler, not to the program**: it changes how the program is built, and itself executes nothing at run time. Pascal writes directives as special comments — **{$R+}** switches range checking on, {$R−} off; others govern overflow checks, input/output checks, debug information. The directive's home is the exact place it stands: a switch rules the text after it until switched again. Removing all directives changes no algorithm — it changes the **safety and shape of the building**.
2. **C++'s preprocessor — directives before the compiler** — C++ gives this work to a **preprocessor** that runs **before** compilation, driven by lines beginning with **#**: **#include** inserts a whole file's text (the libraries' headers), **#define** names a text substitution used through the program, **#ifdef / #endif** include or exclude whole parts of the text by condition. The famous first line of every C++ program, `#include <iostream>`, is a directive — the program's first word is spoken not to the machine, but to the builder about where its tools live.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An instruction to the compiler — changing how the program is built, executing nothing at run time
2. As special comments — {$R+} and its kin
3. Range checking
4. The text after it, until switched again

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A program talks to two audiences: the machine that will run it, and the compiler that must first build it. Grade 10's vocabulary chapter closes with the messages meant for the second audience. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of directives — orders to the builder as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of c++'s preprocessor — directives before the compiler in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of directives — orders to the builder → the student studies the picture and names what each part shows
- GIF — a GIF of c++'s preprocessor — directives before the compiler in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
