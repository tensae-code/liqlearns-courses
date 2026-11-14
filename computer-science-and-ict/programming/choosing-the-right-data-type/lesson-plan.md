# Lesson plan — Choosing the Right Data Type

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Choosing the Right Data Type
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to choose and use the right data type for each value — by the kind of value, its range, and what the program will do with it (Malaysia, Tingkatan 4)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Choose by the value and its range** — The first questions are about the **value**: is it whole or decimal (int against double), a single character or text (char against String), a truth (boolean)? Then its **range**: a class mark fits a byte, a population does not — too small a type **overflows**, silently wrapping or failing; too large a type merely wastes space. Malaysia's order is value first, range second: the kind of the value names the family, the range settles the member.
2. **Choose by the job — and pay for wrong choices** — The second questions are about the **job**: a value that will be **calculated with** must be numeric — a phone number kept as int loses its leading zero and invites arithmetic it will never need, so it belongs in String; a mark kept as String cannot be averaged. Wrong choices charge rent throughout the program: conversions at every use, comparisons that sort as text ('10' before '9'), totals that refuse to add. Choosing the type is choosing what the value **can do** — the lesson's rule is to decide it once, at declaration, from the value's kind and career, not from the first value it happens to hold.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The value — whole or decimal, character or text, truth or not
2. The value's range
3. It overflows — silently wrapping or failing
4. String — as int it loses its leading zero and invites arithmetic it never needs

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every value in a program must live somewhere, and the type of that somewhere is a decision. Malaysia's Java chapter teaches type choice as a skill of its own. In this lesson you learn to choose by the value, its range, and its job — and what each wrong choice costs. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of choose by the value and its range as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of choose by the job — and pay for wrong choices in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of choose by the value and its range → the student studies the picture and names what each part shows
- GIF — a GIF of choose by the job — and pay for wrong choices in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
