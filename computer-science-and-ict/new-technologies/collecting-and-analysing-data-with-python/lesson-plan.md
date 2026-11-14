# Lesson plan — Collecting and Analysing Data With Python

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Collecting and Analysing Data With Python
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** data collection and analysis using Python — loading a data file and displaying it in full (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Loading — the file becomes a table** — Python analysis begins by **loading a data file** — a CSV or similar — into a table structure (with the data library, a DataFrame): the file's rows become the table's rows, its first line the column names. Loading is checked, not assumed: the shape (rows × columns), the column names and types, and the first and last rows are inspected, because a file silently misread — a shifted column, a swallowed header — poisons every later number while looking like success.
2. **Displaying in full — meeting the whole data** — Jordan insists on **displaying the data in full** at the start: the whole table printed or scrolled, not a sample — so the analyst's eye meets the missing values, the strange entry, the column that is all one value, before any statistic hides them inside an average. Only after the full look do the unit's later tools (statistics, charts) earn their turn. The habit is the lesson: in Python the commands are short, so the discipline must be deliberate — load, look at everything, then analyse.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A table — rows as rows, first line as column names
2. A DataFrame (with the data library)
3. The shape, the column names and types, the first and last rows
4. Poisons every later number while looking like success

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The unit's theory ends; the practice begins at the file. This lesson loads real data into Python and looks at all of it — the analyst's first honest act. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of loading — the file becomes a table as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of displaying in full — meeting the whole data in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of loading — the file becomes a table → the student studies the picture and names what each part shows
- GIF — a GIF of displaying in full — meeting the whole data in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
