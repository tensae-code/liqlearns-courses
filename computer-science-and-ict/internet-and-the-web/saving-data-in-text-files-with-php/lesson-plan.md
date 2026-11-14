# Lesson plan — Saving Data in Text Files with PHP

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Saving Data in Text Files with PHP
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How data is produced and stored in text files by server-side PHP — the program writes records as lines of text that outlive the page (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Why a text file — data that outlives the page** — Server data must **outlive** any single page visit: names signed up today are read tomorrow. A **text file** is the unit's store: plain lines of characters, kept in a file on the server, readable by the program and by people. Each **record** is written as **one line**, its **fields separated by a chosen mark** (such as a comma or a | ) — Aina|aina@mail.com|2026 — so the line can later be split back into its fields. The format is an agreement the whole unit keeps: writer and reader must use the same mark and the same field order, or the data reads as nonsense.
2. **Writing — from program values to stored lines** — In PHP the writing follows a fixed rhythm: **open** the file for appending (so old records are kept), **write** the new record as one formatted line (the fields joined by the mark, ended by a newline), and **close** the file. Appending matters: opening a file for plain writing **replaces** its contents, and the difference between keeping a term's sign-ups and keeping only the last one is that single choice. Malaysia's check is performed by eye: after saving, the file is opened as text and **read** — if the new line does not stand correctly among the old, the writing, not the idea, is repaired.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Names signed up today are read tomorrow — the page forgets; the file stays
2. A text file on the server — plain lines of characters
3. As one line, its fields separated by a chosen mark
4. Open the file, write the line, close the file

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A page forgets everything when it closes — unless its data was written somewhere that stays. Malaysia's PHP unit keeps its data in the humblest store: text files on the server. In this lesson you produce and save data as text, line by line. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of why a text file — data that outlives the page as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of writing — from program values to stored lines in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of why a text file — data that outlives the page → the student studies the picture and names what each part shows
- GIF — a GIF of writing — from program values to stored lines in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
