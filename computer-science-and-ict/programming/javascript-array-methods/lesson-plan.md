# Lesson plan — JavaScript Array Methods

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** JavaScript Array Methods
**Place in the curriculum:** ICT expansion — Armenia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Armenia's Digital Literacy and Computer Science books (Armenia Grade 12 G12 student, Armenia Grade 12 G12 teacher), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** JavaScript array methods — the ready-made operations on arrays: pushing, popping, joining, mapping, filtering and friends (Armenia Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Changing the array — push, pop, shift, unshift, splice** — JavaScript arrays carry built-in **methods**. The end-and-start family changes the array itself: **push** adds at the end, **pop** removes from the end, **unshift** adds at the start, **shift** removes from the start, and **splice** removes or inserts at any position. Each returns something useful — push returns the new length, pop and shift return the removed element. Armenia's Grade 12 student book closes with a reference section on array methods (p. 75) — the course's own quick-lookup, kept at the back like a dictionary.
2. **Working over the array — join, slice, map, filter, forEach** — The second family works *over* the array without necessarily changing it: **join** builds a string from the elements, **slice** copies a chosen stretch, **forEach** runs a function on every element, **map** builds a new array of transformed elements, and **filter** builds a new array of only the elements that pass a test. The modern style prefers map/filter over hand-written loops: the code says *what* (double them; keep the passing ones) and the method does the walking. Searching joins the family too — **indexOf** finds a value's place, and **includes** answers yes or no.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Armenia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. push
2. pop (from the end) and shift (from the start) — each returns the removed element
3. Remove or insert at any position, not only at the ends
4. The array's new length

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 12's reference section is a toolbox for arrays. This lesson learns the tools. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of changing the array — push, pop, shift, unshift, splice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of working over the array — join, slice, map, filter, foreach in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of changing the array — push, pop, shift, unshift, splice → the student studies the picture and names what each part shows
- GIF — a GIF of working over the array — join, slice, map, filter, foreach in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
