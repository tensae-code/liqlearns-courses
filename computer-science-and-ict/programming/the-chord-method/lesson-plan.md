# Lesson plan — The Chord Method

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Chord Method
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The chord method (false position): refine a bracket not by halving but by the chord — the straight line between the bracket's ends crosses zero nearer the root than the midpoint, when the function is honest about its slope (Moldova Grade 12, Informatică, §3.9).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The chord's crossing — values, not only signs** — Draw the **chord** — the straight segment joining the points (a, f(a)) and (b, f(b)). Where it crosses the x-axis, at **c = a − f(a)·(b − a) / (f(b) − f(a))**, stands the method's next estimate: the root as if the function were its chord. Test f(c) and **replace the end whose f has the same sign as f(c)** — the bracket narrows, always keeping opposite signs, but from the side the values accuse. The midpoint was democracy; the chord is cross-examination.
2. **Speed and its condition — the honest slope** — When the function is **nearly straight** across the bracket, the chord's crossing lands almost on the root: convergence in a few steps where bisection needed dozens. The method's assumption is exactly that honesty: a **strongly curving** function can make one bracket end **stick** (its f always losing the comparison), narrowing from one side only — slower, but still bracketed, still certain, because the sign discipline is never surrendered. The stopping rule serves both methods: when the bracket (or the step |c_new − c_old|) is under the demanded precision, report c with its bound.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The straight segment joining (a, f(a)) and (b, f(b))
2. Its crossing with the x-axis — the next estimate c
3. The end whose f has the same sign as f(c) — so the bracket keeps opposite signs
4. They accuse the nearness — the root sits nearer the end whose |f| is smaller

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Bisection ignores the function's values; it only reads their signs. Grade 12's second method listens to the values too: if one end is barely positive and the other hugely negative, the root is surely near the small end. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the chord's crossing — values, not only signs as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of speed and its condition — the honest slope in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the chord's crossing — values, not only signs → the student studies the picture and names what each part shows
- GIF — a GIF of speed and its condition — the honest slope in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
