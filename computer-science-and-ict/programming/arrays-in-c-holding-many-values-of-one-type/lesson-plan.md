# Lesson plan — Arrays in C — Holding Many Values of One Type

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Arrays in C — Holding Many Values of One Type
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** arrays in C: one name holding many values of one type — declaring, initialising and indexing them, with the index counting from zero (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Declaring and initialising — one name, many rooms** — An **array** holds **many values of one type** under **one name**: `int marks[30];` declares thirty int rooms. It may be **initialised** at birth with a list — `int days[7] = {31, 28, 31, 30, 31, 30, 31};` — and its size is fixed at declaration: C arrays do not grow. The type rule is strict — every room holds the array's one type — which is the array's bargain: order and speed in exchange for sameness.
2. **Indexing — counting from zero, and the edge** — Rooms are reached by **index**: `marks[0]` is the **first** room, `marks[29]` the thirtieth and last — C counts from **zero**, so the last index is always **size − 1**. The loop and the array are made for each other: a for loop walking i from 0 to size−1 visits every room exactly once, which is how arrays are filled, summed and searched (the linear-search placement's home ground). The edge is unforgiving: C does **not check** an index — `marks[30]` reaches into memory that is not yours and reads or writes a stranger's value silently. The boundary is the programmer's own discipline: the loop's condition is the fence, and it must be written like one.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Many values of one type under one name
2. int marks[30];
3. No — its size is fixed
4. A list of values in braces

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Thirty students, thirty marks. Declare thirty variables and your program drowns in names before it computes anything. The array is the rescue: one name, thirty numbered rooms. In C the rescue comes with C's honesty — fixed size, no mercy at the edges — and both halves are this lesson. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of declaring and initialising — one name, many rooms as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of indexing — counting from zero, and the edge in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of declaring and initialising — one name, many rooms → the student studies the picture and names what each part shows
- GIF — a GIF of indexing — counting from zero, and the edge in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
