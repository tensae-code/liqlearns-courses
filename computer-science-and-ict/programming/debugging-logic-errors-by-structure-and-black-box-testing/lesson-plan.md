# Lesson plan — Debugging Logic Errors by Structure — and Black-Box Testing

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Debugging Logic Errors by Structure — and Black-Box Testing
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Hunting logic errors where they hide — in selection, repetition, arrays and subprograms — and testing a program from outside, black-box (Greece Grade 12, supplementary material Unit 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Where logic errors hide — structure by structure** — The unit sorts the hunt by the structure under suspicion. In **selection**: the condition's edges (what happens *at* the boundary value?) and the branch that was never taken in testing. In **repetition**: the loop that runs once too few or too many, and the variable never updated inside it. In **arrays**: the index that steps one place too far, the loop bound that skips the last place. In **subprograms**: the parameter passed in the wrong order, the local name shadowing the caller's. Each structure has its own favourite hiding places, and the debugger checks them in that structure's order.
2. **Black-box testing — judging from outside** — **Black-box testing (μαύρο κουτί)** tests the program **from its statement alone**: the tester chooses inputs — typical, boundary and hostile — computes the **expected** answers by hand from what the program *should* do, runs it, and compares, never reading the code and so never excused by it. A mismatch convicts the program, not the test. Beside the error-kind teaching of the same unit (syntactic errors, abnormal-termination errors, logic errors), black-box testing is the standing method: it finds logic errors precisely because it refuses to be told where to look kindly.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. By structure — selection, repetition, arrays, subprograms
2. The condition's edges and the branch never taken in testing
3. A loop running once too few or too many (or a variable never updated inside it)
4. An index one place too far (or a bound skipping the last place)

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A logic error does not announce itself; the program runs and lies politely. Greece's supplementary unit teaches the hunt as a craft: search structure by structure, and test from outside without trusting the code's own story. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of where logic errors hide — structure by structure as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of black-box testing — judging from outside in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of where logic errors hide — structure by structure → the student studies the picture and names what each part shows
- GIF — a GIF of black-box testing — judging from outside in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
