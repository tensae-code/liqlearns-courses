# Lesson plan — Descriptive Statistics in Python

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Descriptive Statistics in Python
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** descriptive statistics analysis in Python — summarising data with the measures of centre and spread (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Centre — mean, median, mode** — Python's data library computes the centre in a line each: the **mean** (the total shared equally — sensitive to every value, dragged by extremes), the **median** (the middle value — unmoved by extremes), and the **mode** (the most frequent value — the only centre a kind can have). Choosing among them is the analyst's judgement, not the library's: incomes take the median, shoe sizes the mode, and reporting the mean alone for dragged data is the oldest statistical sleight.
2. **Spread and shape — range, deviation, the summary** — Centre without spread lies politely: two classes can share a mean and differ in everything else. The spread measures: **range** (max − min), **standard deviation** (the typical distance from the mean — the spread with a unit and a meaning), and the quartiles. Python's `describe()` gathers the family into one summary table — count, mean, deviation, min, quartiles, max — which Jordan teaches as the analyst's first page on any new column: read it whole before quoting any one number from it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Mean, median, mode
2. It is dragged by extremes
3. For dragged data — incomes
4. The most frequent value — the only centre a kind can have

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Four hundred numbers become five: the average, the middle, the most common, the lowest, the spread. This lesson computes the five in Python — and learns what each can hide. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of centre — mean, median, mode as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of spread and shape — range, deviation, the summary in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of centre — mean, median, mode → the student studies the picture and names what each part shows
- GIF — a GIF of spread and shape — range, deviation, the summary in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
