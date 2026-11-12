# Lesson plan — Entities — declare once, reference by name

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Entities — declare once, reference by name
**Place in the curriculum:** Title — Internet and the Web in the Computer Science and ICT ladder (TITLES.md); stocked from Ethiopia's Grade 12 book, Unit 4 — Web Authoring. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** an entity is a name declared once to stand for a piece of text; writing &name; in the document makes the parser put the full text in its place — including the guide's author-and-copyright textbook example (teacher guide — evidence).
**This lesson's own level:** it stands on the entity-references lesson — the learner already uses the five predefined references; this doing lesson declares new entities of their own.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Declaring and using an entity (doing)** — an entity stands in place of content or markup and must be declared before use; an internal parsed entity is declared with an ENTITY declaration tying a name to replacement content, then used as &name;
2. **The textbook example — author and copyright by entity (teacher guide — evidence)** — a complete internal DTD answer defines author and copyright entities once and uses them inside a textbook element, so the output assembles the author and copyright lines

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Whitespace and entity references in XML. Recommended, never forced.

## What the learner can do when it ends
1. Declare an internal parsed entity tying a name to replacement text.
2. Use the reference form &name; in a document.
3. Read the guide's textbook example: author and copyright entities assembled by the parser (teacher guide — evidence).

## What you need
Paper and a pencil; a computer with a text editor and a browser helps.

## The run of the lesson (in order)
1. **Do it first** — the learner finds the short token standing in for a long publisher line, and guesses where the long line is defined, before declarations are named (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30910]: a picture of a short reference token expanding into a full publisher line — the student follows the reference from its declaration to its expanded place in the document.
   - ADD GIF [GIF 30922]: an entity reference expanding into its full text as the parser processes it — the student watches the short reference grow into the full publisher text.
   - ADD AUDIO: a voice reading the lesson's key words and code aloud — the student listens and repeats each term.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30910] — a short reference token expanding into a full publisher line → the student follows the reference from its declaration to its expanded place in the document.
- GIF [GIF 30922] — an entity reference expanding into its full text as the parser processes it → the student watches the short reference grow into the full publisher text.
- AUDIO — the lesson's key words and code read aloud → the student listens and repeats.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Uses an entity before declaring it → an entity must be declared before use.
- Forgets the & or the ; → the reference form is the name between & and ; — both marks are part of it.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 4 — Web Authoring). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
