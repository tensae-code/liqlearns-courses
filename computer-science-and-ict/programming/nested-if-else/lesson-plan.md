# Lesson plan — Nested if-else

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Nested if-else
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A nested if-else is a selection placed inside another selection's branch: the outer test narrows the situation, the inner test decides within it — used when the second question only makes sense after the first is answered, and kept readable by strict indentation that shows which else belongs to which if.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **A choice inside a choice** — **Nesting** puts an if-else **inside the branch** of another: if the outer condition holds, the inner if-else runs and picks between its two ways; if not, the outer else runs. The inner question is only asked when the outer answer makes it meaningful — pass the exam first, **then** ask distinction or plain pass.
2. **Indentation and the dangling else** — Nesting multiplies a known danger: an **else pairs with the nearest unmatched if**, whatever the writer intended — so **indentation** must honestly mirror the pairing, and braces should wrap branches whenever misreading is possible. The book teaches nesting through **exercises** (§3.24): trace each by walking the conditions in order and marking the one path taken.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A selection inside another selection's branch.
2. When the second question only makes sense after the first.
3. The nearest unmatched if.
4. Braces around branches.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Some decisions come in layers: first whether, then which kind. This lesson builds selections inside selections — and keeps them readable. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a choice inside a choice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of indentation and the dangling else in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a choice inside a choice → the student studies the picture and names what each part shows
- GIF — a GIF of indentation and the dangling else in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
