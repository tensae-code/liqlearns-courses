# Lesson plan — Declaring Variables in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Declaring Variables in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Variable declarations in the dual course: Pascal's var section — names gathered before begin — against C++'s declarations placed where needed, each with name, type, and optional initial value (Moldova Grade 10, Informatică, §2.10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Pascal's var section — all names before the work** — In Pascal, variables are declared in the **var section** between the heading and begin: `var a, b: integer; x: real;` — several names may share one type in one line. The declaration **reserves memory, fixes the type, and introduces the name** for the whole block; a variable not declared does not exist for the compiler, and using one is the beginner's first error message. Declaration is not assignment: a fresh variable's value is **undefined** until the program gives it one.
2. **C++'s declarations — where needed, with initial values** — C++ allows a declaration **wherever an instruction may stand**, and lets it carry an **initial value**: `int a = 5;` declares and assigns in one breath — and a for loop may declare its own steer in its heading: `for (int i = 0; …)`. The freedom has a shadow discipline: a name exists only **from its declaration to the end of its block** — C++'s first sight of the scope Grade 12 formalises. Pascal's gathered var section trades that freedom for a single census of a block's data, read at a glance.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. In the var section, between the heading and begin
2. Yes — var a, b: integer;
3. Reserves memory, fixes the type, introduces the name
4. Undefined — until the program assigns one

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Data enters a program through declarations: the act that brings a variable into existence with a name and a type. The pair's two placements of that act — all up front, or where needed — is a real design difference. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of pascal's var section — all names before the work as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of c++'s declarations — where needed, with initial values in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of pascal's var section — all names before the work → the student studies the picture and names what each part shows
- GIF — a GIF of c++'s declarations — where needed, with initial values in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
