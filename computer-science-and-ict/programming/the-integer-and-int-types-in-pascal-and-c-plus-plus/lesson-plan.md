# Lesson plan — The Integer and int Types in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Integer and int Types in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Whole-number types in the dual course: Pascal's integer family and C++'s int family — signed and unsigned, their sizes and ranges, and the arithmetic (including / against div, % for remainder) that each performs (Moldova Grade 10, Informatică, §2.2).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **A family of sizes — and the sign choice** — Both languages offer whole numbers in **several sizes**: Pascal's family runs from shortint and byte through **integer** to longint; C++'s from short through **int** to long. Each size fixes a **range** (2ⁿ patterns). Every size also offers an **unsigned** twin (Pascal's byte/word; C++'s unsigned int) that spends all its patterns on 0 and positives, doubling the top at the price of negatives. Choosing a whole-number type is choosing **range and sign** together — and knowing both before the data arrives.
2. **Integer arithmetic in the pair — division's two answers** — The pair agrees on +, −, * and disagrees, instructively, on division. Pascal splits it: **/** gives a real, **div** the whole quotient, **mod** the remainder. C++'s **/** on two ints *is* Pascal's div — the whole quotient, fraction discarded — and **%** is its mod: 7 / 2 is 3 in C++ integers, 7 % 2 is 1. The same symbols, different contracts: the dual course's recurring lesson — **the type and the language together fix what an operator does**, never the symbol alone.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. shortint, byte, integer, longint
2. short, int, long
3. A range — 2ⁿ patterns
4. 0 and positives only — doubling the top at the price of negatives

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 7 met integer alone; Grade 10 takes it up in both languages at once. The family is larger than one type: sizes, signs and remainders all differ between the pair — and the differences are examinable. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a family of sizes — and the sign choice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of integer arithmetic in the pair — division's two answers in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a family of sizes — and the sign choice → the student studies the picture and names what each part shows
- GIF — a GIF of integer arithmetic in the pair — division's two answers in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
