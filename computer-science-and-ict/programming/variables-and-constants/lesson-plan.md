# Lesson plan — Variables and Constants

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Variables and Constants
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The difference between a variable and a constant — a variable's value can change while the program runs; a constant's value is fixed and must not change (Malaysia teaches this in Python, Tingkatan 2, and again in Java, Tingkatan 4)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Variables — values that change** — A **variable** is a named store whose value **can change** while the program runs: a score starts at 0 and grows, a name is read in and replaced next run. In Python a variable is made by assigning (score = 0) and its type follows the value it holds; in Java it is declared with its type (int score = 0;). Changing a variable is normal work — assignment replaces the old value entirely; the old value is gone unless it was copied elsewhere first.
2. **Constants — values that are fixed** — A **constant** (pemalar) is a named store whose value is **fixed when it is set and must not change** during the run: pi, the passing mark, the number of days in a week. Languages guard them differently — Python uses the capital-name convention (PI = 3.14159, a promise by the programmer), Java uses the keyword **final** (final int PASS_MARK = 50;), which the compiler enforces. Constants exist so fixed values have **one home**: change the rule once, in one place, and every use follows; a constant that could change silently would be a variable wearing a false name.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A named store whose value can change while the program runs
2. A named store whose value is fixed when set and must not change during the run
3. By assigning — score = 0; its type follows the value
4. Pi; the passing mark (also: days in a week)

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Two named boxes hold a program's values. One may change a hundred times a run; the other must never change at all. Malaysia teaches the pair formally in two school years and two languages. In this lesson you learn the difference — and why a program needs both kinds. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of variables — values that change as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of constants — values that are fixed in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of variables — values that change → the student studies the picture and names what each part shows
- GIF — a GIF of constants — values that are fixed in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
