# Lesson plan — Bucket Sort

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Bucket Sort
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How bucket sort works — scattering values into buckets by their range, ordering each bucket, then gathering the buckets in order (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Scatter — values into their buckets** — **Bucket sort** begins with **buckets**: ranges that cover the values — for marks out of 100, buckets 0–9, 10–19, …, 90–100. Every value is **placed in the bucket its size belongs to** — 37 into the 30s bucket, 8 into the 0s bucket. No comparisons between values happen in this step; the value's own size names its bucket. Scattering works when the ranges are known in advance and the values spread across them — a list of ages, marks or prices fits; a list with no known range does not.
2. **Order each bucket, then gather** — Inside each bucket, the few values are put **in order** (by a simple sort — the buckets are small, so even bubble sort is quick there). Then the buckets are **gathered in bucket order** — all of the 0s bucket, then all of the 10s, and so on — and the gathered line is the sorted list. Malaysia pairs bucket sort with bubble sort to make the contrast explicit: bubble sort moves values by comparing neighbours; bucket sort moves them by knowing where values of each size belong.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A range that the values are scattered into — such as 0–9, 10–19 for marks
2. By its own size — 37 goes in the 30s bucket
3. No — the value's size names its bucket
4. Its few values are put in order — by a simple sort

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Not every sort compares neighbours. Malaysia's second sort scatters the values into labelled buckets — tens in one, twenties in the next — gathers each bucket in order, and reads the buckets through. In this lesson you bucket-sort, and learn the kind of data it suits. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of scatter — values into their buckets as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of order each bucket, then gather in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of scatter — values into their buckets → the student studies the picture and names what each part shows
- GIF — a GIF of order each bucket, then gather in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
