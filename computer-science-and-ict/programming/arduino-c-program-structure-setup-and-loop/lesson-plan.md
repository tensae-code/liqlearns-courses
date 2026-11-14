# Lesson plan — Arduino C Program Structure — setup() and loop()

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Arduino C Program Structure — setup() and loop()
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 12 G12 Informatika student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Arduino C program structure — every Arduino program (a sketch) in the C language has the same skeleton: setup() runs once at the start, loop() repeats forever (Indonesia Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The skeleton — two functions every sketch has** — An Arduino program — a **sketch** — is written in **C**, and every sketch, from a blinking light to the smart bin, has the same basic structure (struktur dasar): two functions the board's system calls. **`void setup()`** holds what happens **once**, when the program starts: setting pin modes, starting the serial connection, preparing the parts. **`void loop()`** holds the program's life: when it finishes, the board calls it again, forever, until power ends. Indonesia's Grade 12 course teaches the skeleton before the commands, because every later line of Arduino code is filed in one of these two rooms.
2. **Writing in the skeleton — order, braces and the one-time test** — The structure disciplines the writing: a command belongs in setup() if it must happen exactly once, in loop() if it is the behaviour repeated. The text rules of Arduino C ride on the skeleton — statements end with **semicolons**, blocks live inside **curly braces**, and `void` names a function that returns nothing. The beginner's standing fault is a one-time act written in loop() (a pin re-set a thousand times a second) or a behaviour trapped in setup() (run once, then silence). Read any sketch by its rooms and the program's whole shape is visible at a glance.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A sketch — written in the C language
2. setup() and loop()
3. Once, when the program starts
4. One-time preparation — pin modes, starting serial, preparing the parts

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Arduino C program structure — every Arduino program (a sketch) in the C language has the same skeleton: setup() runs once at the start, loop() repeats forever (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the skeleton — two functions every sketch has as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of writing in the skeleton — order, braces and the one-time test in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the skeleton — two functions every sketch has → the student studies the picture and names what each part shows
- GIF — a GIF of writing in the skeleton — order, braces and the one-time test in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
