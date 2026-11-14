# Lesson plan — Building a Number Converter in PHP

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Building a Number Converter in PHP
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** The form in the visitor's browser; the conversion on the server.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The converter as a web page — form, server, answer** — In the PHP telling, the converter's parts change their homes. The **form** — number field, from-system and to-system choices, convert button — lives in the visitor's browser. On submit, the values travel to the **server**, where the PHP reads them, **validates** them (a binary field holding a 2 is refused here, exactly as in the desktop project), runs the **conversion**, and **generates the answer page**. The visitor's experience is one honest round trip: type, send, read. Everything the Grade 11 course taught about dynamic pages — request, processing, generated answer — is spent here on Grade 12's mathematics.
2. **Same algorithms, second world — the project's point** — Not one conversion rule changes: repeated division for decimal-out, place values for decimal-in, groups of four bits between binary and hexadecimal. That is the project's argument, made by building it: the **algorithm** is the durable possession; VB.NET forms and PHP pages are two temporary houses for it. The testing discipline travels too — the PHP converter is checked against the same hand-worked conversions as its desktop twin, and a difference between the twins is a fault in a house, never in the mathematics. With this subject, Unit One closes as Unit Two will: learn the thing, build it twice, and finish able to say what stayed the same — because that, and only that, is what was actually learned.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The form in the visitor's browser; the conversion on the server.
2. The values travel to the server; PHP reads, validates, converts, and generates the answer page.
3. The algorithm — the two languages are temporary houses for it.
4. The same hand-worked conversions as its VB.NET twin.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The second telling of Egypt's Grade 12 Unit One project: the same number converter, produced in PHP — the systems, the algorithms and the checks unchanged, the whole machine rebuilt as a web page that converts on the server and returns the answer as a page. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the converter as a web page — form, server, answer as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of same algorithms, second world — the project's point in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the converter as a web page — form, server, answer → the student studies the picture and names what each part shows
- GIF — a GIF of same algorithms, second world — the project's point in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
