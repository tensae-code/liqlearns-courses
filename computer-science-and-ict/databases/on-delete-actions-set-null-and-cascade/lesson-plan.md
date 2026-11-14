# Lesson plan — ON DELETE Actions — SET NULL and CASCADE

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** ON DELETE Actions — SET NULL and CASCADE
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** What happens to the child rows when a parent is deleted — ON DELETE SET NULL and its alternatives, in Kuwait's related tables
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **SET NULL — the child stays, the pointing ends** — **ON DELETE SET NULL** answers a parent's deletion by **emptying the children's foreign key**: the child rows **stay** — a student remains a student — but their link now points at **nothing (NULL)**, honestly unassigned until a new parent is given. It fits children whose existence does not depend on the parent: the record is real, only its belonging is ended.
2. **CASCADE and the other alternatives — choosing the fate in advance** — **ON DELETE CASCADE** answers with the opposite mercy: the children are **deleted with the parent** — right where a child is meaningless alone (an order's lines without the order). The remaining alternatives refuse or restrict the deletion while children exist. The lesson's discipline is that the fate is **chosen when the table is created**, written into its FOREIGN KEY declaration — not improvised on the day a parent must go.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. What happens to child rows when their parent is deleted
2. Empties their foreign key — the rows stay, pointing at nothing
3. Where the child's existence does not depend on the parent
4. Deletes the children with the parent

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Deleting a parent is the dangerous mirror of updating one: the children still point at it. Kuwait's relational year names what may happen to them — and makes the pupil choose it in advance, in the table's own declaration. This lesson is the delete actions. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of set null — the child stays, the pointing ends as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of cascade and the other alternatives — choosing the fate in advance in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of set null — the child stays, the pointing ends → the student studies the picture and names what each part shows
- GIF — a GIF of cascade and the other alternatives — choosing the fate in advance in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
