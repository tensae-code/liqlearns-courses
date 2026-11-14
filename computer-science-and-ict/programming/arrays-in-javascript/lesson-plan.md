# Lesson plan — Arrays in JavaScript

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Arrays in JavaScript
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How arrays are used in JavaScript — one name holding many values in order, reached by index from 0, looped over, and changed with the array's own methods (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Building and reaching — indexes from zero** — A JavaScript **array** holds **many values under one name**, in order: let marks = [70, 85, 60, 92];. Each value is reached by its **index** — its position counted **from 0**: marks[0] is 70, marks[1] is 85. The array's **length** (marks.length) counts its values, so the last index is always length − 1. An index outside the array answers **undefined** — JavaScript does not stop the script, which makes index discipline the programmer's own duty: indexes run 0 to length − 1, never 1 to length.
2. **Looping and changing** — Arrays are worked **by loop**: a for loop running i from 0 to length − 1 visits every value in order — the shape behind totalling, searching and printing a list. Arrays **change**: a value is replaced by assignment (marks[2] = 65;), new values are added at the end with **push**, and removed from the end with **pop**. Malaysia's scripts put array and loop together for the page's real work — a class's marks totalled, a list of names printed, a highest mark found — the array is the script's memory of many, the loop its way of visiting them all.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Many values under one name, in order
2. From 0 — marks[0] is the first value
3. 60
4. By a for loop running i from 0 to length − 1

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Five marks, thirty names, a term of temperatures: a script needs one name for the whole collection. Malaysia's JavaScript chapter gives it the array. In this lesson you build, read, loop and change JavaScript arrays. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of building and reaching — indexes from zero as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of looping and changing in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of building and reaching — indexes from zero → the student studies the picture and names what each part shows
- GIF — a GIF of looping and changing in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
