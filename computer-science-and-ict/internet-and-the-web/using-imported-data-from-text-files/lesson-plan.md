# Lesson plan — Using Imported Data from Text Files

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Using Imported Data from Text Files
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How data imported from text files is used — the program reads the lines back, splits each line into fields, and works with them as its own data (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Reading back — lines into records** — Reading reverses writing: the program **opens** the text file, reads it **line by line** (or reads the whole file as a set of lines), and **splits each line** at the agreed separator into its **fields** — the inverse of the joining that stored it. The newline at each line's end is trimmed, or it rides into the last field and poisons comparisons. Malaysia's discipline is symmetry: the reader is written **from the writer's format agreement** — same separator, same field order — and any change to the stored format must change both, or neither.
2. **Using the records — lists, searches, answers** — With fields in hand, the records become the program's working data: **listed** on a page (the guestbook shows its entries), **searched** (does this name already exist?), **counted and totalled**, and used to **answer** the visitor (a login read against the stored sign-ups). The unit's name for the flow is **imported data**: data made elsewhere — by an earlier visit, another program, or a person typing the file — taken in and used as the program's own. The test of an import is a round trip: store three records by the writing program, import them by the reading program, and the three records that come back must be the three that went in, field for field.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Writing — open, read line by line, split each line into fields
2. The joining that stored the record
3. The newline — or it rides into the last field and poisons comparisons
4. Listing on a page; searching; counting and totalling (also: answering a login)

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Stored lines are only half the work; the other half is using them again. Malaysia's PHP unit reads its text files back and puts the records to work. In this lesson you import: read, split, and use. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of reading back — lines into records as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of using the records — lists, searches, answers in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of reading back — lines into records → the student studies the picture and names what each part shows
- GIF — a GIF of using the records — lists, searches, answers in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
