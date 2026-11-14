# Lesson plan — Von Neumann Architecture

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Von Neumann Architecture
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Almost every computer today follows one stored-program design: the program and the data it works on live together in the same memory, and a processor fetches instructions from that memory one after another, carries them out, and repeats.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **One memory for program and data** — In the **von Neumann architecture** the computer keeps **both** in the **same memory**: the **data** being worked on and the **program** — the list of instructions that says what to do with it. Because the program itself is stored, it can be loaded, changed and replaced like any other data, which is why one machine can run many different programs. The memory is a row of numbered cells (addresses), and each instruction or value sits in a cell the processor can name.
2. **The processor at work — fetch, decode, execute** — The **central processing unit (CPU)** works in a steady cycle: **fetch** the next instruction from memory, **decode** it (work out what it asks for), then **execute** it — with the **control unit** directing the traffic and the **arithmetic-logic unit (ALU)** doing the sums and comparisons. Registers hold the instruction being carried out and the values in play. The single shared path between processor and memory is the design's famous narrow point — the von Neumann bottleneck.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The program and the data it works on.
2. One machine can load and run many different programs.
3. Fetch, decode, execute.
4. Sums and comparisons — the arithmetic and logic.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every program you have ever run was stored somewhere before it ran. This lesson shows the one design that made that normal: program and data sharing a single memory. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one memory for program and data as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the processor at work — fetch, decode, execute in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one memory for program and data → the student studies the picture and names what each part shows
- GIF — a GIF of the processor at work — fetch, decode, execute in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
