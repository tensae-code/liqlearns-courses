# Lesson plan — The Rectangle Method for the Approximate Definite Integral

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Rectangle Method for the Approximate Definite Integral
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The rectangle method: a definite integral — the area under a curve — approximated by a sum of rectangles on equal subintervals, with left, right and midpoint heights, and error that shrinks as the rectangles narrow (Moldova Grade 12, Informatică, §3.10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Areas from rectangles — the sum that approximates** — The **definite integral** of f over [a, b] is the **area under its curve** (above the axis, on that span). The **rectangle method** cuts [a, b] into **n equal subintervals** of width **h = (b − a) / n**, stands a **rectangle** on each — its height a function value in that subinterval — and takes the **sum of the rectangles' areas** as the integral's approximation: Σ f(xᵢ)·h. As n grows and h shrinks, the staircase hugs the curve closer, and the sum approaches the true area — a method error the refinement literally pictures.
2. **Left, right, midpoint — choosing the height** — The height choice gives the method its three school forms: **left rectangles** take f at each subinterval's **left end** (under-shooting a rising function), **right rectangles** at the **right end** (overshooting it), and **midpoint rectangles** at the **centre** — whose errors from the two sides of the curve partly cancel, making it the most accurate of the three for smooth functions. For a monotone function, left and right sums **bracket the truth** between them — the integral's own separation interval — and their difference bounds the error of either.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The area under the curve over [a, b]
2. n equal subintervals of width h = (b − a) / n
3. The sum of the rectangles' areas — Σ f(xᵢ)·h
4. h shrinks, the staircase hugs the curve, the sum approaches the true area

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Some areas have no formula. Grade 12's last numerical method builds them from the one area everyone knows — the rectangle's — many times over. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of areas from rectangles — the sum that approximates as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of left, right, midpoint — choosing the height in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of areas from rectangles — the sum that approximates → the student studies the picture and names what each part shows
- GIF — a GIF of left, right, midpoint — choosing the height in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
