# Lesson plan — Maintaining a Database

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Maintaining a Database
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Database maintenance: the standing care of a living database — compacting and repairing its file, backing it up, splitting and protecting it — so the data survives its own growth and its machines (Moldova Grade 12, Informatică, §4.15).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Compact and repair — the file healed and shrunk** — Deleting records and objects in Access **does not shrink the file**: the space stays claimed, as gaps — the file **bloats**, slows, and over years can corrupt. **Compact and Repair** is the cure: it **rebuilds the database file** — records recopied in order, gaps dropped, indexes rebuilt, and detected damage repaired where possible. The course's rule makes it a routine, not a rescue: compact **regularly** (weekly in working databases, always after mass deletions), and only ever on a **copy kept safe** until the compacted file proves sound.
2. **Backup, splitting and protection — the standing care** — The rest of maintenance is standing defence. **Backups**: dated copies of the file, kept apart from the working machine, on a rhythm the data's value sets — the only true repair for corruption, theft or fire. **Splitting**: a working database is divided into a **back-end** (tables only, on the shared place) and **front-ends** (queries, forms, reports on each user's machine), so many users share data without sharing damage. **Protection**: passwords and permissions keep the merely curious and the careless from the tables. Maintenance is unglamorous and decisive: databases rarely die of hard questions — they die **unkept**.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Deleted records and objects leave claimed, empty gaps — the file does not shrink
2. Rebuilds the file — records in order, gaps dropped, indexes rebuilt, damage repaired where possible
3. Regularly — weekly in working databases, and always after mass deletions
4. On a copy kept safe until the compacted file proves sound

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The Access course ends not with a query but with a duty. A database that is used grows, fragments and is one accident away from loss; maintenance is the set of habits that keep it alive. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of compact and repair — the file healed and shrunk as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of backup, splitting and protection — the standing care in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of compact and repair — the file healed and shrunk → the student studies the picture and names what each part shows
- GIF — a GIF of backup, splitting and protection — the standing care in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
