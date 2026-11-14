# Lesson plan — The Programs That Make Up an Operating System

**Course:** Computer Science and ICT · **Title:** Software · **Lesson:** The Programs That Make Up an Operating System
**Place in the curriculum:** ICT expansion — Uzbekistan (2026-11-14) — in the title Software on the ICT course ladder (TITLES.md). Built new from Uzbekistan's informatics student books (Russian-language editions), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** An operating system is made of **programs**: the **loader** that starts the system when the machine switches on, the **kernel** that manages memory, the processor's time and the devices, **drivers** that speak to each device, and the **utilities and interface programs** the user meets.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The parts of the system** — An operating system is made of **programs**: the **loader** that starts the system when the machine switches on, the **kernel** that manages memory, the processor's time and the devices, **drivers** that speak to each device, and the **utilities and interface programs** the user meets. Uzbekistan's Grade 8 book gives the composition its own lesson, right after the concept of an operating system.
2. **How the parts work together** — At switch-on the loader brings the kernel in; the kernel starts the drivers and the interface; from then on every program asks the kernel for memory, time and devices, and the kernel shares them fairly and guards them. Name the parts and the booting of a computer stops being magic: it is a queue of programs, each starting the next.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Software on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Uzbekistan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. No — a set of programs.
2. The loader.
3. The kernel.
4. The drivers and the interface.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — 'The operating system' sounds like one thing. Grade 8's lesson takes it apart: an operating system is a set of programs, each with its own job in starting and running the machine. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the parts of the system as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of how the parts work together in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the parts of the system → the student studies the picture and names what each part shows
- GIF — a GIF of how the parts work together in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
