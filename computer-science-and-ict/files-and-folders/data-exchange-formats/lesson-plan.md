# Lesson plan — Data Exchange Formats

**Course:** Computer Science and ICT · **Title:** Files and Folders · **Lesson:** Data Exchange Formats
**Place in the curriculum:** ICT expansion — Armenia (2026-11-14) — in the title Files and Folders on the ICT course ladder (TITLES.md). Built new from Armenia's Digital Literacy and Computer Science books (Armenia Grade 6 G6 student, Armenia Grade 6 G6 teacher), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** data exchange formats — the agreed shapes (plain text, CSV, XML, JSON and friends) that let different programs and computers swap data (Armenia Grade 6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Why exchange needs a format — agreement before sending** — Programs store data in their own internal shapes, which other programs cannot read. A **data exchange format** is an agreed public shape for handing data over: both sides know how the data is laid out, so the receiver can rebuild it. The simplest is **plain text**; a table travels as **CSV** (values separated by commas, one row per line). Armenia's Grade 6 book teaches 'general concepts of data exchange formats' as its own lesson (§17) — the concept before the tools.
2. **Structured formats — XML and JSON, and choosing between them** — Data with inner structure travels in **XML** (data wrapped in named tags, like <name>…</name>) or **JSON** (data written as name–value pairs and lists, borrowed from JavaScript). Both are text, so humans can read and debug them; both need the two sides to agree on the names. Choosing a format asks: Is it a flat table (CSV), a structured document (XML), or program data (JSON)? Is it readable by people? Will the receiver's program accept it?

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Files and Folders on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Armenia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Each program stores data in its own internal shape, which others cannot read
2. An agreed public shape for handing data over, so the receiver can rebuild it
3. Plain text
4. Values separated by commas, one row per line

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Two programs that have never met can still swap data — if they agree on a shape. This lesson learns those shapes. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of why exchange needs a format — agreement before sending as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of structured formats — xml and json, and choosing between them in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of why exchange needs a format — agreement before sending → the student studies the picture and names what each part shows
- GIF — a GIF of structured formats — xml and json, and choosing between them in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
