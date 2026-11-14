# Lesson plan — Combining Search or Sort

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Combining Search or Sort
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to choose between search and sort for a job — and combine them when the job needs both in the other order: search within sorting, and sorting by searching (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Reading the job — search, sort, or both** — The choice is read off the job's **question**. A job asking **whether or where** a value is — with no need for the list afterwards in order — is a **search** job. A job asking for the list **itself in order** — a ranking, a timetable, a price line — is a **sort** job. A job asking repeated where-questions **and** an ordered list is **both**. Malaysia's discipline is to refuse the unneeded half: sorting a list to answer one where-question wastes the sort; searching a list that must be handed over ordered leaves the job undone.
2. **The other weaving — each inside the other** — The two also live **inside** each other: sorting methods **search** as they work (bubble sort's passes search for out-of-order pairs; finding the smallest remaining value is a search repeated inside a selection-style sort), and a search can be **served by a partial sort** (bucket sort's scattering is a search-by-size that half-sorts as it places). Recognising the inner job explains the outer one's cost: a sort built on repeated searching takes repeated-search time. The chapter's final skill is this reading — naming the jobs inside the job before choosing the algorithm.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The job's question
2. A search job
3. A sort job — a ranking, a timetable, a price line
4. Sorts search as they work — for out-of-order pairs, or for the smallest remaining value

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Not every combination is sort-then-search. Malaysia's chapter closes by putting the choice itself on the table: some jobs need only a search, some only a sort, and some weave the two the other way round. In this lesson you learn to read a job and know which it is. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of reading the job — search, sort, or both as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the other weaving — each inside the other in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of reading the job — search, sort, or both → the student studies the picture and names what each part shows
- GIF — a GIF of the other weaving — each inside the other in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
