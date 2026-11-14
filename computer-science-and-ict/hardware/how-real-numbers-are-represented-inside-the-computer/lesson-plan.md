# Lesson plan — How Real Numbers Are Represented Inside the Computer

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** How Real Numbers Are Represented Inside the Computer
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Floating-point representation: a real number is stored as sign, exponent and mantissa — a fixed count of bits split three ways — which is why reals have both a range and a precision, and why most decimals are stored approximately (Moldova Grade 11, Informatică, §3.7).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Sign, exponent, mantissa — the three fields** — A real is stored as **three fields in a fixed row of bits**: the **sign** (0 for +, 1 for −), the **exponent** (a shifted power of two), and the **mantissa** (the number's significant digits in binary, normalised so its first digit is 1). The value is **sign × mantissa × 2^exponent** — the binary twin of the written form 1.25×10³. Doubling a field's share widens what it governs: more exponent bits, a **wider range**; more mantissa bits, **finer precision**. The fixed total is the budget both are paid from.
2. **Range and precision — the two edges of the compromise** — The representation has **two edges**. Beyond the exponent's reach lie numbers **too large (overflow)** and **too small (underflow toward zero)** — the type's range. Between two neighbouring stored mantissas lie all the true values that must share them — the type's **precision limit**, the reason 0.1 is stored as a close stranger and errors accumulate in long computations (Grade 12's error lessons are seated here). The compromise is chosen, not suffered: science needs range and the school needs honesty about precision — the floating point is both, in one row of bits.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Sign, exponent and mantissa
2. sign × mantissa × 2^exponent
3. The mantissa's first digit is 1
4. Wider range; finer precision

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Integers got fixed patterns; reals cannot have them — between 0 and 1 alone there are infinitely many. Grade 11's representation chapter ends with the computer's ingenious compromise: the floating point. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of sign, exponent, mantissa — the three fields as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of range and precision — the two edges of the compromise in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of sign, exponent, mantissa — the three fields → the student studies the picture and names what each part shows
- GIF — a GIF of range and precision — the two edges of the compromise in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
