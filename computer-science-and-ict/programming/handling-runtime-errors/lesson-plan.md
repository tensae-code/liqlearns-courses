# Lesson plan — Handling Runtime Errors

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Handling Runtime Errors
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Errors that appear only while the program runs — division by zero, missing files, impossible values — and handling them instead of crashing (Greece Grade 12, Anaptyxi Efarmogon Ch.13)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Runtime errors — the kind only the run reveals** — A **runtime error (σφάλμα εκτέλεσης)** is a fault that appears **while the program executes**: the data it meets breaks an operation — **division by zero**, a root of a negative number, a file that is not there, a value too large for its type. It differs from its two brothers: the **syntax error**, caught by the translator before the run, and the **logic error**, which runs quietly to a wrong answer. The runtime error **stops** the run — abnormal termination — unless the program was built expecting it.
2. **Handling — expecting the blow and answering it** — **Handling** a runtime error means building the program's answer **before** the blow lands: **check the dangerous data first** (is the divisor zero? does the file exist? is the value in range?) and give the program an honest road when the check fails — a message that names the trouble, a fresh chance to input, a safe ending instead of a crash. The chapter's rule is a design rule: every operation that *can* break on data must be met by its check, because the run will meet every data the writer did not imagine.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A fault that appears while the program executes, when the data breaks an operation
2. Division by zero; a file that is not there (also root of a negative, value too large for its type)
3. Syntax is caught by the translator before the run; runtime appears in the run
4. A logic error runs quietly to a wrong answer; a runtime error stops the run

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The syntax is perfect. The logic is sound. Then a user types 0 for the divisor and the program dies in front of them. Runtime errors are the third kind of error — the kind only the run can reveal. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of runtime errors — the kind only the run reveals as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of handling — expecting the blow and answering it in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of runtime errors — the kind only the run reveals → the student studies the picture and names what each part shows
- GIF — a GIF of handling — expecting the blow and answering it in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
