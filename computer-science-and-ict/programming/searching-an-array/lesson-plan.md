# Lesson plan — Searching an Array

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Searching an Array
**Place in the curriculum:** ICT expansion — Mongolia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Mongolia's student books (Ministry of Education, Culture and Science(s) of Mongolia, Ulaanbaatar), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Finding an element in an array — linear search through the elements in order, the found-index variable that reports where (or that it is absent), and the improvement that stops the search at the first match
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Linear search and the found-index** — **Linear search** looks for a value by walking the array **in order**, testing each element against the wanted value. Its report is kept in the **found-index variable**: the position where the value was found, or the agreed sign — nothing found — when the walk ends without a match. The two outcomes are equally the search's duty: 'it stands at place 7' and 'it is not here' are both knowledge, and a search that can only say the first is unfinished. The book's programs ask the array real questions — is this mark present, where does this name stand — and the found-index is the answer's shape.
2. **Stopping at the first match — the improvement** — The first version walks on even after success, finishing the array out of habit. The **improvement** is one decision: **stop at the first match** — the moment the found-index is set, the walk ends. The saving is real (on average half the array unwalked) and the lesson inside it is larger: an algorithm is **improvable** — the correct first version is a floor, not a ceiling, and the programmer's craft includes returning to working code with a colder eye. Mongolia pairs the two array lessons deliberately: sorting made the array orderly, searching makes it answerable — and both were taught as methods to be understood, traced and improved, not incantations to be memorised.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Mongolia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It walks the array in order, testing each element against the wanted value
2. The variable reporting where the value was found — or the agreed 'nothing found' sign
3. To report the place, or to report absence — both are knowledge
4. It walks on after success, finishing the array out of habit

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The array is filled and sorted; now it must answer questions. Mongolia's search lesson is the humblest search there is — look at each element until the wanted one appears — taught with the care that makes humble methods honest. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of linear search and the found-index as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of stopping at the first match — the improvement in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of linear search and the found-index → the student studies the picture and names what each part shows
- GIF — a GIF of stopping at the first match — the improvement in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
