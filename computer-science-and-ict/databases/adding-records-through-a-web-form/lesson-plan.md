# Lesson plan — Adding Records Through a Web Form — the Add_Term Page

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Adding Records Through a Web Form — the Add_Term Page
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Takes a term typed into a web form and stores it as a new record in the MySQL database.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The form — where the journey starts** — The page opens with an **HTML form**: fields for the term, its meaning and its illustration, and a submit button. The form's job is **gathering and naming** — each field carries a **name**, because that name is how the receiving page will know which typed value is which. A well-built form also guards the journey's first step: required fields marked, lengths matching the database table's columns, so what the visitor sends is already shaped like what the database can hold. Egypt builds this page inside the dictionary project, where the need is real: a dictionary that cannot grow is a poster, not a dictionary.
2. **The PHP receiving page — from submission to stored record** — On submit, the browser sends the named values to **Add_Term.php**, whose PHP code **reads** each value by its field name, **checks** it (present, sane, safe to store), and runs the **INSERT** that adds one new **record** to the dictionary table in MySQL — then answers the visitor: added, or not added and why. The faults the book makes pupils hunt are the journey's own: a field name mistyped between form and page (the value arrives as nothing), a check skipped (an empty term stored), a success claimed before the insert ran. When the page works, the circle closes — the next visitor who searches the dictionary finds the term this visitor added.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Takes a term typed into a web form and stores it as a new record in the MySQL database.
2. Gathering and naming — each field's name tells the receiving page which value is which.
3. INSERT — adding one new record to the dictionary table.
4. Whether the term was added — or not added, and why.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The most complete single page in Egypt's Grade 11 project: Add_Term.php, where a visitor's typed term travels from a web form, through a PHP page, into the MySQL database — the full circle of the dynamic web, built by pupils as one named page. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the form — where the journey starts as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the php receiving page — from submission to stored record in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the form — where the journey starts → the student studies the picture and names what each part shows
- GIF — a GIF of the php receiving page — from submission to stored record in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
