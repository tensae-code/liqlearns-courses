# Lesson plan — Libraries and Packages in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Libraries and Packages in Python
**Place in the curriculum:** ICT expansion — Nepal (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Nepal's *Computer Science, Class 10*, because no existing lesson teaches Python libraries and packages as its own lesson.
**The one thing this lesson teaches:** Python code is shared in ready-made collections — a module is one file of code, a package is an organised folder of modules, and a library is a collection of packages and modules — and `import` brings that ready-made code into your program so you can call its functions instead of writing everything yourself.
**This lesson's own level:** It stands on user-defined functions — code of your own, written once and called by name; modules, packages, libraries and `import` are built inside the lesson from Unit 4 §4.3 of Nepal's book.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Modules, packages and libraries — ready-made code, in growing bundles** — A module is a single Python file holding functions and other code; a package gathers related modules in one organised folder; a library is the whole collection a programmer draws on — Python's standard library arrives with Python itself, and other libraries, like pandas, are added to it.
2. **Bringing code in with `import`** — `import` loads a module into your program; you call its functions through the module's name (`math.sqrt(16)`), or bring one function in by name with `from ... import` and call it directly.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: User-Defined Functions in Python in Programming. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Nepal's own way is kept: in Nepal's book libraries and packages (§4.3) follow user-defined functions — your own functions first, then everyone else's — and the same book later puts a library to work: file handling with pandas in §4.6.

## What the learner can do when it ends
1. Say what a module, a package and a library each are, and how they grow from one to the next.
2. Say what the standard library is and name libraries Nepal's own course uses (math and turtle's kin; pandas for file work).
3. Use `import` to bring a module in and call one of its functions through the module's name.
4. Use `from ... import` to bring one function in by name, and say how the call differs.

## What you need
A computer with Python — the lesson's imports (math, turtle) are in the standard library, so nothing has to be installed.

## The run of the lesson (in order)
1. **Do it first** — Your own functions let you reuse *your* code. But a square root, a drawing turtle, a table of data from a file — must every programmer in the world write those from nothing, every time? This lesson opens the shared shelves: code written once by someone, kept in bundles, and brought into your program with one word. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the three bundles nested: one module file, a package folder holding several module files, and a library shelf holding several packages — the student points from the smallest bundle to the largest and names each.
   - ADD IMAGE: a picture of a program with an arrow marked `import math` bringing a toolbox labelled math into it, and the call `math.sqrt(16)` reaching into the toolbox — the student traces the arrow and the call and says which name belongs to the module and which to the function.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the three bundles nested: a module file, a package folder of modules, a library shelf of packages → the student points from smallest to largest and names each.
- IMAGE — a picture of `import math` bringing a toolbox into a program, and `math.sqrt(16)` reaching into it → the student traces the arrow and the call and names module and function.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Calls `sqrt(16)` after plain `import math` and gets a name error → with `import math` the function keeps its module's name in front: `math.sqrt(16)`. The bare name works only with `from math import sqrt`. Tries to import a library that is not installed → the standard library arrives with Python; outside libraries like pandas must be installed first — an import can only bring in what is there. Thinks importing copies the code into their file → import *loads and links* the module; the code stays in its own file and is shared, not copied.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
