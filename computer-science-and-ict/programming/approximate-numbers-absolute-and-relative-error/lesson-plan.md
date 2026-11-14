# Lesson plan — Approximate Numbers — Absolute and Relative Error

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Approximate Numbers — Absolute and Relative Error
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Approximation measured: a measured or computed number stands for a true value it is not — the absolute error bounds the difference, the relative error bounds it against the value's size (Moldova Grade 12, Informatică, §3.5).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Approximate numbers — the true value and its stand-in** — An **approximate number** is a value used **in place of a true value** it differs from: measurements (a length read to the nearest millimetre), rounded values (π as 3.14159), and the machine's stored reals are all stand-ins. The **absolute error** is the size of the difference: **|true − approximate|** (or a bound on it, written a ± Δa). Rounding to n decimals gives an absolute error of at most **half a unit of the last kept place** — the standing price of every rounding, known before it is paid.
2. **Relative error — error against size** — The **relative error** divides the absolute error by the value's size: **δ = Δa / |a|** — often spoken as a **percentage**. It, not the absolute error, judges quality: an error of 1 mm is excellent in a kilometre of road and disgraceful in a 3 mm screw. Relative error travels through computations as their health record — the sections after this one track how it is born (at measurement, at rounding) and how operations grow it. A number without its error is only half reported: exactness is a claim, error is the evidence.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A value used in place of a true value it differs from
2. Measurements, rounded values, and the machine's stored reals
3. The size of the difference |true − approximate| — or a bound on it
4. a ± Δa

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Numerical modelling begins with an honest admission: most numbers a computer holds are approximations. This section gives approximation its two measures — so 'close' stops being a feeling and becomes a number. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of approximate numbers — the true value and its stand-in as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of relative error — error against size in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of approximate numbers — the true value and its stand-in → the student studies the picture and names what each part shows
- GIF — a GIF of relative error — error against size in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
