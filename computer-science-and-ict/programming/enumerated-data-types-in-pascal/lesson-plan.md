# Lesson plan — Enumerated Data Types in Pascal

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Enumerated Data Types in Pascal
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Enumerated types in Pascal: a type the programmer defines by listing its values — days, suits, colours — where the order of the list gives the values their order (Moldova Grade 7, Informatică, §6.8).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Defining a type by listing its values** — An **enumerated type** is defined by **listing its values in brackets**: `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — the type has exactly those values and no others. A variable of the type holds one of them: `var d: TDay; d := Wed;`. The values are **names, not texts**: they are not strings in apostrophes, and the compiler checks them — assigning `d := Holiday` is an error the moment it is written, protection no number code (1=Mon, 2=Tue…) can give.
2. **Order from the list — ord, succ, pred** — The list's order is not decoration: it gives the values an **order**. The functions **succ** and **pred** give the next and previous value (succ(Wed) = Thu), and **ord** gives a value's position counted from 0 (ord(Mon) = 0). So enumerated values can be compared (Sat > Fri is true), stepped through in loops, and counted — the manners of numbers, with the meanings of names. Enumerations suit closed lists of the world: months, suits, directions, school grades — sets that do not grow.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. By listing its values in brackets in a type definition
2. Mon, Tue, Wed, Thu, Fri, Sat, Sun — the type TDay
3. No — they are names, not texts in apostrophes
4. The compiler checks assignments — a value outside the list is an error at once

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Some data is not numbers at all: a day of the week is one of seven named things. Grade 7's Pascal course reaches the type the programmer builds themselves — by enumerating, listing, its values. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of defining a type by listing its values as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of order from the list — ord, succ, pred in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of defining a type by listing its values → the student studies the picture and names what each part shows
- GIF — a GIF of order from the list — ord, succ, pred in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
