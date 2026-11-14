# Lesson plan — VLOOKUP in Excel

**Course:** Computer Science and ICT · **Title:** Spreadsheets · **Lesson:** VLOOKUP in Excel
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Spreadsheets on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 10 G10T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** VLOOKUP in Excel — looking a value up in a table and bringing back its partner (Jordan Grade 10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What VLOOKUP does** — **VLOOKUP(lookup_value, table, column, exact)** searches the **first column** of a table for the lookup value, walks across that row, and returns the value in the stated **column**. It is the spreadsheet's join: any two tables sharing a key (a pupil number, a product code) can lend each other their columns. The V is **vertical** — the search runs down a column; its sibling HLOOKUP runs across a row, and the book's data lesson needs the vertical one because records live in rows.
2. **Exactness and the lookup's faults** — The fourth argument is the lesson's conscience: **FALSE demands an exact match** (the code must be found, or the formula reports #N/A — an honest failure), while TRUE accepts the nearest — right for tax bands, catastrophic for names. The standing faults: lookup values in the table's first column **only** (a table arranged otherwise cannot be searched), duplicates returning the **first** match silently, and numbers stored as text failing to meet their twins. Jordan teaches VLOOKUP with its faults attached because a lookup that fails silently invents data — and #N/A, loudly, is the analyst's friend.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Spreadsheets on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The first column of a table, for the lookup value
2. The value in the stated column of the found row
3. The spreadsheet's join — tables lending columns through a shared key
4. Vertical — the search runs down a column

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The marks sheet has pupil numbers; the names live in another table. Joining them by hand is an afternoon; VLOOKUP does it in a formula. This lesson learns the lookup. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of what vlookup does as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of exactness and the lookup's faults in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of what vlookup does → the student studies the picture and names what each part shows
- GIF — a GIF of exactness and the lookup's faults in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
