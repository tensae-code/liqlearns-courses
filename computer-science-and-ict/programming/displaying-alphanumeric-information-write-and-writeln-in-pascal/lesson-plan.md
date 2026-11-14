# Lesson plan — Displaying Alphanumeric Information — write and writeln in Pascal

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Displaying Alphanumeric Information — write and writeln in Pascal
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How a Pascal program shows results: write and writeln (and C++'s cout) display numbers, characters and texts — alphanumeric information — with formats that control width and decimals (Moldova Grade 8 §3.7 and Grade 10 §3.8).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **write and writeln — showing values and texts** — **write** displays its parameters and leaves the cursor where it stopped; **writeln** displays and then moves to a **new line**. The parameters may be **numbers, characters, strings in apostrophes, or whole expressions** — each is evaluated and shown in turn: `writeln('Sum = ', s)` prints the text, then the value of s. Showing **alphanumeric information** — letters and digits together, the screen's whole alphabet — is these two procedures' job; C++ does the same work with `cout <<`.
2. **Formats — width and decimals** — A parameter may carry a **format**: `write(x:8)` reserves **8 positions** for x, right-aligned in its field — the trick that builds straight columns in tables; `write(r:8:2)` adds **2 decimals** for a real. Unformatted reals print in long exponent form, so formats are not decoration but legibility: money with two decimals, tables with aligned columns, labels glued to values with spaces inside the strings. The display is the program's face to its user — this section teaches it as a craft, not an afterthought.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. write leaves the cursor where it stopped; writeln moves to a new line after displaying
2. Numbers, characters, strings in apostrophes, and whole expressions
3. The text 'Sum = ', then the value of s
4. Letters and digits together — everything the screen can show as text

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A program that computes in silence is half a program. Two Moldova books teach the showing as its own instruction family: write and writeln, the voices of every Pascal program in the course. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of write and writeln — showing values and texts as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of formats — width and decimals in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of write and writeln — showing values and texts → the student studies the picture and names what each part shows
- GIF — a GIF of formats — width and decimals in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
