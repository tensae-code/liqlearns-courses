# Lesson plan — Project — Face Recognition with a Database

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Project — Face Recognition with a Database
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Kuwait's AI-and-database integration project, in both Grade 11 terms — detecting faces with the OpenCV Haar cascade and logging them in SQLite (face_logs/attendance), growing into an employees-and-face_log system with queries, decision reports and ReportLab PDF reports
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Detection, recognition, and the log — the Term 1 build** — The project separates two acts pupils confuse: **detection** — finding that a face is in the picture, and where — and **recognition** — saying whose it is. Detection is done with OpenCV's **Haar cascade**, a trained detector that scans the image for face patterns. What the camera sees is then **logged in an SQLite database** — a face_logs / attendance table of who was seen and when — because, as the book insists, **a database beats a text file**: the log can be queried, counted and kept honestly, not merely appended and forgotten.
2. **The Term 2 growth — employees, queries and reports that decide** — Term 2 grows the logger into a system: an **employees table linked to a face_log table** (the relational year's parent and child), Haar detection feeding the log, and **queries and reports that support decisions** — who was late how often, which door saw whom — finished as **PDF reports built with ReportLab**, the program itself printing its findings. The project's lesson is the integration: neither the AI nor the database is the product — the product is a system whose seeing is remembered, questioned, and reported.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Detection finds that a face is present and where; recognition says whose it is
2. OpenCV's Haar cascade
3. In an SQLite database — a face_logs / attendance table
4. The log can be queried, counted and kept honestly

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Two of Kuwait's courses meet in one project: the AI that sees faces, and the database that remembers them. Grade 11 builds it in Term 1 as an attendance logger and grows it in Term 2 into an employee face-log system with reports. This lesson is that integration, in both its forms. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of detection, recognition, and the log — the term 1 build as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the term 2 growth — employees, queries and reports that decide in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of detection, recognition, and the log — the term 1 build → the student studies the picture and names what each part shows
- GIF — a GIF of the term 2 growth — employees, queries and reports that decide in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
