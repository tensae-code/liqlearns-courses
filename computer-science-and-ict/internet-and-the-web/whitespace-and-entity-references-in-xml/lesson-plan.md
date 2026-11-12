# Lesson plan — Whitespace and entity references in XML

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Whitespace and entity references in XML
**Place in the curriculum:** Title — Internet and the Web in the Computer Science and ICT ladder (TITLES.md); stocked from Ethiopia's Grade 12 book, Unit 4 — Web Authoring. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** XML keeps all whitespace instead of collapsing it, and special characters must be written as entity references — five predefined ones, with < and & strictly illegal as themselves.
**This lesson's own level:** it stands on the first syntax rules — the learner's documents are well formed in root, case and nesting; this doing lesson adds the last two syntax rules.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Whitespace — XML keeps it all (doing)** — XML does not truncate multiple white spaces; HTML collapses them to one
2. **Entity references — the five predefined swaps (doing)** — characters with special meaning are replaced by entity references; the five predefined ones cover < > & ' "; only < and & are strictly illegal, replacing > too is good habit

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Well-formed XML — root, case and nesting rules. Recommended, never forced.

## What the learner can do when it ends
1. Say how XML treats multiple white spaces, and how HTML differs.
2. Write the five predefined entity references.
3. Say which two characters are strictly illegal and which swap is good habit.

## What you need
A computer with a text editor and a browser; paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — the learner writes a line containing a < sign as content, opens it, and meets the parser's error before entity references are named (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30907]: a picture of a sentence keeping all its spaces, beside a < being swapped for its reference — the student traces the wide gap that survives, then reads the swapped reference aloud.
   - ADD AUDIO: a voice reading the lesson's key words and code aloud — the student listens and repeats each term.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30907] — a sentence keeping all its spaces, beside a < being swapped for its reference → the student traces the wide gap that survives, then reads the swapped reference aloud.
- AUDIO — the lesson's key words and code read aloud → the student listens and repeats.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Expects spaces to collapse → XML does not truncate them; HTML does.
- Writes a bare & in content → & must be written as its reference, like <.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 4 — Web Authoring). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
