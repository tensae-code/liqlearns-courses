# Lesson plan — The Bisection Method

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Bisection Method
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The bisection method: halve the bracket, keep the half that still changes sign, repeat — a root-hunt that is slow, simple and utterly certain, with the error halving at every step (Moldova Grade 12, Informatică, §3.8).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Halve and keep the sign change** — Given a **bracket [a, b]** (f of opposite signs at its ends), bisection computes the **midpoint** c = (a + b) / 2 and tests f(c): the half-interval whose ends **still change sign** becomes the new bracket — if f(a)·f(c) < 0, the root is in [a, c]; else in [c, b]. Each step halves the cage. The root itself is never computed — it is **cornered**, until the cage is smaller than the demanded precision and any point of it (the midpoint, say) may be reported as the root, with the cage's width as its error bound.
2. **The arithmetic of certainty — error and step count** — After **n steps**, the bracket's width is **(b − a) / 2ⁿ** — certainty you can count in advance: to squeeze [0, 1] below 10⁻³ needs 10 steps (2¹⁰ = 1024). Bisection will never run away, never divide by a slope, never be fooled by the function's shape — its price is this **fixed, unhurried rate** (one binary digit of precision per step), which faster methods beat when they behave and disgrace themselves when they don't. The method is the chapter's benchmark of honesty: certainty first, speed as a luxury.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Halves the bracket and keeps the half whose ends still change sign
2. By the sign of f at the midpoint — f(a)·f(c) < 0 keeps [a, c]
3. No — it is cornered; a cage-point is reported with the cage's width as error bound
4. A bracket from separation — f of opposite signs at the ends

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The first refining method Grade 12 teaches is the tortoise of numerical methods: it cannot be fooled, it cannot be hurried, and its error is known to the digit at every step. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of halve and keep the sign change as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the arithmetic of certainty — error and step count in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of halve and keep the sign change → the student studies the picture and names what each part shows
- GIF — a GIF of the arithmetic of certainty — error and step count in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
