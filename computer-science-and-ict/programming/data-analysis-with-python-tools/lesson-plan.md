# Lesson plan — Data Analysis with Python Tools

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Data Analysis with Python Tools
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Data analysis draws meaning out of clean data by asking it questions — totals, averages, groupings, comparisons and patterns over time — and Python's data tools make those questions fast: load the table, group and sort it, compute the summaries, and read what the numbers say back.
**This lesson's own level:** It stands on cleaning and organising data (analysis needs ready data) and on the Python lessons. The mathematics is school-level: sums, averages, comparisons. The new skill is making the tool do the counting.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What data analysis asks** — Analysis is **questioning a table**. The standard questions recur everywhere: **totals and counts** (how much, how many), **averages** (the typical value), **grouping** (split the data by a column — by class, by subject, by month — and summarise each group), **comparison** (groups against each other, this year against last), and **patterns** (does a value rise, fall, or move with another?). Every finding is one of these questions answered. The craft is choosing the question that matches the decision at stake: 'results fell' is a complaint; 'results fell in mathematics, in Grade 9, in the second term' is a finding someone can act on.
2. **Doing it with Python tools** — Python's data tools (the lesson works with its table-handling libraries) follow a steady rhythm. **Load** the clean table into the program. **Select** the columns and rows the question needs. **Group** by the chosen column and **compute** the summaries — sum, count, average — for each group. **Sort** the results so the biggest fall or the highest group stands first. Then **read**: the output is still just numbers until the analyst states what they mean in words a decision-maker can use. The tool does the counting in seconds; the thinking — which question, which grouping, what the answer means — stays human, and garbage groupings give garbage findings as surely as dirty data did.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Name the standard analysis questions: totals/counts, averages, grouping, comparison, patterns.
2. Describe the Python rhythm: load, select, group, compute, sort, read.
3. Explain why the grouping chosen decides what finding is possible.
4. Turn a vague complaint ('results fell') into an analysable question and state its finding in words.

## What you need
A computer with Python and its data tools, and a clean sample table from the teacher. Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — The clean table from the last lesson sits in front of you: four hundred pupils, their subjects, their marks. A head teacher asks: which subject fell furthest? Do girls and boys differ? Is the fall in one class or everywhere? Answering by hand would take a week of counting. With Python's tools it takes an afternoon — if you know what questions to ask. This lesson is about the asking. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a big table with five speech bubbles above it — 'how many in total?', 'what is typical?', 'split it by class', 'this year against last?', 'is it rising or falling?' — the student reads the bubbles and says which kind of question each is.
   - ADD GIF: a GIF of a table on a screen splitting into coloured groups by class, each group shrinking to its average, the groups lining up tallest to shortest — the student watches once, then says which step of the rhythm each moment shows.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a big table with five speech bubbles above it — 'how many in total?', 'what is typical?', 'split it by class', 'this year against last?', 'is it rising or falling?' → the student reads the bubbles and says which kind of question each is
- GIF — a GIF of a table on a screen splitting into coloured groups by class, each group shrinking to its average, the groups lining up tallest to shortest → the student watches once, then says which step of the rhythm each moment shows
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Runs computations before choosing a question → the tool will happily total anything; decide what decision the answer must serve, then group for it. Stares at output numbers without a finding → force the last step: finish the sentence 'This means that…' in plain words, or the analysis is not done.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
