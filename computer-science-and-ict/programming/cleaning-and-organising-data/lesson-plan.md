# Lesson plan — Cleaning and Organising Data

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Cleaning and Organising Data
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Organising data puts collected data into one clear structure — a table with agreed columns and formats — and cleaning it repairs the 'dirty data': missing values, wrong formats, duplicates, impossible entries and inconsistent spellings, until the data is trustworthy enough to analyse.
**This lesson's own level:** It stands between collecting data and analysing it in the general process. It needs care and judgement more than technique; a spreadsheet or a simple table is the working tool.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Spotting dirty data — the five faults** — Collected data is dirty in five recurring ways. **Missing values**: an entry left blank where the analysis will need it. **Wrong formats**: the same kind of value written in different shapes — 'fifteen', 15, '15 yrs'. **Duplicates**: the same record entered twice, quietly doubling its weight. **Impossible entries**: an age of 150, a date of 32 January — values that cannot be true, born of slips. **Inconsistent spellings**: one village under three names, which a counting program will treat as three villages. Spotting them is a skill of its own: scan each column asking 'what shapes appear here, and do they agree?'
2. **Cleaning and organising — the repairs** — Cleaning repairs each fault by its own rule, decided **before** touching the data and applied the **same way everywhere**. Formats are unified (all ages as numbers, all dates in one pattern). Spellings are standardised to one agreed name per thing. Duplicates are hunted by their identifying columns and merged or removed. Missing and impossible values are handled honestly: go back to the source if possible; if not, mark them clearly as missing rather than inventing plausible numbers — an invented value is a lie the analysis will repeat with confidence. Around the cleaning sits the **organising**: one table, one row per record, one column per kind of value, headings agreed — the shape every later tool expects.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Name the five faults of dirty data and spot each in a sample table.
2. Say the repair rule for each fault, and why rules are set in advance and applied uniformly.
3. Explain why a missing value must be marked, never invented.
4. Organise a small messy dataset into one clean table (one row per record, one column per kind).

## What you need
Paper, a pencil, and a printed or screen table of messy sample data from the teacher. A spreadsheet helps but is not required.

## The run of the lesson (in order)
1. **Do it first** — Two hundred survey answers arrive. One age is written 'fifteen', one is 15, one is 150. The same pupil appears twice. A whole column of villages is spelled three ways. Nothing here is false exactly — but no program can count it, and no chart can be trusted. The work of this lesson is the rescue: turning that heap into data you would sign your name under. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a table with five problem cells highlighted in five colours — one empty, one word among numbers, one row repeated, one impossible age, one village spelled a new way — the student names the fault in each colour.
   - ADD GIF: a GIF of the messy table from the first sub lesson being repaired cell by cell — words becoming numbers, the double row dissolving, the three village spellings merging into one — until the table stands clean and even — the student watches once and names two repairs they saw.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a table with five problem cells highlighted in five colours — one empty, one word among numbers, one row repeated, one impossible age, one village spelled a new way → the student names the fault in each colour
- GIF — a GIF of the messy table from the first sub lesson being repaired cell by cell — words becoming numbers, the double row dissolving, the three village spellings merging into one — until the table stands clean and even → the student watches once and names two repairs they saw
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Wants to 'just fix' cells one by one as spotted → un-ruled fixing creates new inconsistency (two cleaners, two results); write the rule first, then apply it to every row alike. Tempted to fill a missing age with a likely guess → a guess becomes a fact in every later chart; mark it missing and let the analysis say so honestly.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
