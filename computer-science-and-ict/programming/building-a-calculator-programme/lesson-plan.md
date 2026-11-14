# Lesson plan — Building a Calculator Programme

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Building a Calculator Programme
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh Grade 9 Digital Technology), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** building a calculator programme: gathering the Python pieces — input, variables, arithmetic — into one working programme that takes two numbers and an operation and returns the answer (Bangladesh Grade 9 Digital Technology, Learning Experience 4, Session 7).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The design — what a calculator does** — Before code, the **design**: the programme **asks for two numbers and an operation**, **computes** by the operation chosen, and **prints the result** — input, process, output, the shape of the simple-program lesson, grown to a tool. The design decisions are the programmer's own: ask the operation as a word or a symbol? What happens if the operation is unknown, or the second number is zero and the operation is division? A calculator that answers wrongly with confidence is worse than one that refuses honestly — the design must say what refusal looks like.
2. **The build — selection chooses the operation** — The build hangs on **selection**: an if-elif-else chain reads the operation and sends the numbers to the matching arithmetic — the chain of choices lesson, employed. Each branch computes and the programme prints from one place, so the output's form is written once. The book's session tests the calculator as a team tool is tested: known answers first (2 + 3 must be 5), then the edges — division by zero, a mistyped operation, enormous numbers — and the programme is only finished when the edges behave as the design promised. Pieces, assembled, tested: that is a programme.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Asks, computes and prints — input, process, output
2. Two numbers and an operation
3. An unknown operation, and division by zero
4. It misleads with authority

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — You own the pieces: input read, values stored, arithmetic working. A calculator is what happens when the pieces are assembled with intent — the first complete tool most programmers ever build, and Grade 9 builds it in Python. Assembly is a different skill from the pieces, and it is this lesson's whole subject. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the design — what a calculator does as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the build — selection chooses the operation in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the design — what a calculator does → the student studies the picture and names what each part shows
- GIF — a GIF of the build — selection chooses the operation in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
