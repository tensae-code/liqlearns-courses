# Lesson plan — Type Conversions in C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Type Conversions in C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Type conversion in C++: values change type implicitly (int widening into double, double narrowing into int with its fraction cut) and explicitly by a cast — and the information each road loses or keeps (Moldova Grade 10, Informatică, §3.5).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Implicit conversion — the compiler's quiet road** — In a mixed expression, C++ **converts implicitly**: an int beside a double is **widened** to double before the operation (5 + 2.0 is 7.0), and a char promotes to its code as int. The dangerous direction is the reverse, done just as quietly in an assignment: a double stored into an int is **narrowed — its fraction is cut off**, 7.9 becoming 7, with no error and no warning at default settings. Widening keeps information; narrowing destroys it — silently.
2. **Explicit conversion — the cast, the programmer's signature** — A conversion the programmer orders is written as a **cast**: `(double) n` or `double(n)` — making n be read as a double for this operation, so n / 2 with n = 7 gives 3.5 instead of 3. The cast's virtue is **visibility**: it signs the conversion in the text, telling every reader (and the examiner) that the type change is intended, and where. The section's rule gathers both roads: let widening happen; **cast every narrowing you mean; never let a narrowing happen unmeant**.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It is widened to double before the operation — 5 + 2.0 = 7.0
2. An int — its code number
3. Narrowing — the fraction is cut off: 7.9 becomes 7
4. Widening; narrowing destroys it — silently

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A C++-only section of the dual course — because C++ converts where Pascal refuses. Mixing types in an expression forces the question: who becomes what, and what is lost on the way? (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of implicit conversion — the compiler's quiet road as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of explicit conversion — the cast, the programmer's signature in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of implicit conversion — the compiler's quiet road → the student studies the picture and names what each part shows
- GIF — a GIF of explicit conversion — the cast, the programmer's signature in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
