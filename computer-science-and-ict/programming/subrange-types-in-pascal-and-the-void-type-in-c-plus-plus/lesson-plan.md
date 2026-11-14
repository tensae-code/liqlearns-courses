# Lesson plan — Subrange Types in Pascal — and the void Type in C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Subrange Types in Pascal — and the void Type in C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Two opposite citizens of the type system: Pascal's subrange, a slice of an ordinal type guarded at its borders — and C++'s void, the type of no value at all, marking procedures that return nothing (Moldova Grade 10, Informatică, §2.7–2.7*).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The subrange — Pascal's guarded slice** — The **subrange** (met in Grade 7) is a slice of an ordinal host: `1..31`, `'A'..'Z'`, `Mon..Fri` — a variable holds only values inside the slice, and range checking **stops the program at a violating assignment**. C++ has **no subrange type**: the same honesty must be written by hand, as checks inside the program — the concept survives, the guard changes from the type system to the programmer's discipline. The comparison is the point: what one language enforces, the other must remember.
2. **void — the type of no value** — C++'s **void** names the **absence of a value**: a function declared void **returns nothing** — it is C++'s spelling of Pascal's **procedure**, against value-returning functions. No variable can be of type void; nothing is stored, compared or printed. Its lesson is symmetry's: a type system needs a word not only for every kind of value but for **no value**, so that 'this subprogram only acts' is said in the type itself. Pascal says it with a keyword (procedure), C++ with a type (void) — the pair's neat parting difference.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A slice of an ordinal host type, holding only values inside it
2. Range checking — an error at that line
3. No — the same honesty is written as checks by hand
4. The guard — from the type system to the programmer's discipline

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 10's types chapter pairs two extremes in one sitting: the type that holds *fewer* values than any other, and the type that holds *none*. Together they close the map of what a type can be. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the subrange — pascal's guarded slice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of void — the type of no value in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the subrange — pascal's guarded slice → the student studies the picture and names what each part shows
- GIF — a GIF of void — the type of no value in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
