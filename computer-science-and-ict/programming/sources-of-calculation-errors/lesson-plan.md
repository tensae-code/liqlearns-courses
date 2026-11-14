# Lesson plan — Sources of Calculation Errors

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Sources of Calculation Errors
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Where errors enter a computation: from the model's simplification, from the input data's measurement, from the method's own approximation, and from rounding inside the machine — the four sources, and which can be reduced (Moldova Grade 12, Informatică, §3.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Born before the machine — model and data errors** — The first source is the **model error**: the model simplifies the world (a frictionless fall, a spherical cow of a problem) — the answer is exact *for the model* and off *for the world*, before any computing. The second is the **input-data error**: measurements carry their absolute and relative errors into the computation as its inheritance — no downstream exactness can wash them out. Both are **irreducible at the desk**: they can be shrunk only by a better model or better measuring, never by more arithmetic.
2. **Born in the work — method and rounding errors** — The third source is the **method error**: numerical methods approximate by design — the bisection's half-interval, the rectangle sum's steps — shrinking as the method refines (more steps, narrower intervals), at the price of more work. The fourth is **rounding error**: the machine's finite mantissa rounds at every operation, and billions of operations accumulate the dust — reducible by wider types and by arranging operations kindly (adding smalls before larges). The chapter's bookkeeping rule: **name every answer's error sources before trusting its digits** — a result whose error budget is unknown is an opinion, not a computation.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The gap from the model's simplification — exact for the model, off for the world
2. The measurements' own errors, inherited by the whole computation
3. No — it is irreducible at the desk
4. Only by a better model or better measuring

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Before blaming a wrong answer, Grade 12's modelling chapter holds an inquest. Every numerical answer's error has a birthplace — and there are exactly four places it can be born. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of born before the machine — model and data errors as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of born in the work — method and rounding errors in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of born before the machine — model and data errors → the student studies the picture and names what each part shows
- GIF — a GIF of born in the work — method and rounding errors in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
