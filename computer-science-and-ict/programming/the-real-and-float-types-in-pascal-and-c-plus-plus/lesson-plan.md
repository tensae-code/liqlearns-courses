# Lesson plan — The Real and float Types in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Real and float Types in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Fractional types in the dual course: Pascal's real and C++'s float and double — how a real is stored (mantissa and exponent), single against double precision, and why their arithmetic is approximate in both languages (Moldova Grade 10, Informatică, §2.3).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Mantissa and exponent — how a real is stored** — A real value is stored in two parts: the **mantissa** — the value's significant digits — and the **exponent** — the power of two (or ten, in the written E form) that places the point. Pascal's **real** and C++'s **float** are the school sizes; C++ adds **double**, with roughly twice the mantissa bits — **double precision**. More mantissa bits mean **more exact digits**; more exponent range means larger and smaller magnitudes. No size escapes the principle: between any two stored neighbours, infinitely many true values share the same stored one.
2. **Approximation in practice — the pair's shared rules** — Because storage is approximate, the pair shares its commandments. **Never test reals for exact equality** — test that their difference is small. **Expect accumulation**: many small additions drift. **Format your output**: digits beyond the type's precision are noise the type never stored. And choose float against double by the data: measurements with five honest digits gain nothing from double's fifteen, while money and long computations argue for the wider mantissa. Grade 12's error chapters are this section, grown up.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The mantissa (significant digits) and the exponent (the power placing the point)
2. Pascal's real and C++'s float
3. Roughly twice the mantissa bits — double precision: more exact digits
4. Range — larger and smaller magnitudes

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 10's dual types continue with the fractions. Both languages store a real the same scientific way — a mantissa carried by an exponent — and both therefore inherit the same beautiful flaw: approximation. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of mantissa and exponent — how a real is stored as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of approximation in practice — the pair's shared rules in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of mantissa and exponent — how a real is stored → the student studies the picture and names what each part shows
- GIF — a GIF of approximation in practice — the pair's shared rules in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
