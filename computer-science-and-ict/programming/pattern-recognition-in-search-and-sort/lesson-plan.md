# Lesson plan — Pattern Recognition in Search and Sort

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Pattern Recognition in Search and Sort
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How pattern recognition is used inside search and sort algorithms — the repeating shapes of the methods (halving, passes, buckets) recognised, named and relied on (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The repeating shape of each method** — Every method in the chapter is a **pattern repeated**: linear search repeats **check–next**; binary search repeats **check the middle–halve**; bubble sort repeats **compare neighbours–maybe swap**, pass within pass; bucket sort repeats **place by size**, then gathers. Recognising the pattern means being able to say, at any step, **what happens next and why** — the next check is forced by the pattern, not chosen by the searcher. A trace that surprises you at some step means either the pattern was misrecognised or the algorithm has a fault — the pattern is the standard the trace is checked against.
2. **Using the pattern — predict, choose, trust** — Patterns also **compare** the methods: the check–next pattern grows one step per item, the halving pattern collapses the field, the neighbour pattern must repeat whole passes. Malaysia's use is practical: given a list and a job, the patterns predict the **work** each method will do, and the prediction chooses the method — order the list once if halving will be used often; accept the passes when the list is nearly sorted. Recognising the pattern is what turns four memorised methods into one understood family.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A pattern repeated
2. Check – next
3. Check the middle – halve
4. The pattern was misrecognised, or the algorithm has a fault

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Malaysia's algorithms chapter turns its first technique back on the algorithms themselves: what pattern does each method repeat? In this lesson you recognise the working patterns inside searching and sorting — because a method you can see the pattern of, you can predict, trace and trust. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the repeating shape of each method as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of using the pattern — predict, choose, trust in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the repeating shape of each method → the student studies the picture and names what each part shows
- GIF — a GIF of using the pattern — predict, choose, trust in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
