# Lesson plan — Compiling and Debugging Programs in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Compiling and Debugging Programs in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The working annexes: how a program text becomes a running program — compilation and linking, the compiler's error messages — and debugging, the disciplined hunt for the errors compilation cannot see (Moldova Grade 10, Informatică, Annexes 3 and 5).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Compiling — from text to running program** — **Compilation** translates the whole program text into the machine's language before any of it runs: the **compiler** checks the text against the language's grammar, and a text with **syntax errors does not compile at all** — the compiler lists the errors, by line, in its own terse tongue the annexes teach to read. The translated parts are then **linked** with the libraries' ready pieces into one executable file. Compile-time is the grammar's judgement; a clean compile says the text is *legal* — it does not yet say the program is *right*.
2. **Debugging — hunting the errors the compiler cannot see** — The errors that remain are **runtime and logic errors**: the program runs, and divides by zero, or answers wrong, or loops forever. **Debugging (depanare)** hunts them with a method: **reproduce** the failure on the smallest input, **watch** the values (by inserted prints, or the debugger's stepping and breakpoints — pausing the run at a chosen line to inspect the state), **locate** the first moment the state goes wrong, **fix**, and **test again**. The annexes' stance is the profession's: debugging is not shame — it is half the craft, practised by method, not by staring.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It translates the whole program text into machine language before any of it runs
2. It stops compilation — the compiler lists errors by line
3. The libraries' ready pieces, joined into one executable file
4. That the text is legal — not yet that the program is right

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 10's book ends not with theory but with the workshop: two annexes, one per language, on the two acts every program in the upper grades will pass through — being compiled, and being debugged. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of compiling — from text to running program as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of debugging — hunting the errors the compiler cannot see in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of compiling — from text to running program → the student studies the picture and names what each part shows
- GIF — a GIF of debugging — hunting the errors the compiler cannot see in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
