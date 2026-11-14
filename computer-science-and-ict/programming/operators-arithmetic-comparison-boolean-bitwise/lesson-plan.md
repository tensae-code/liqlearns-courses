# Lesson plan — Operators — Arithmetic, Comparison, Boolean, Bitwise

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Operators — Arithmetic, Comparison, Boolean, Bitwise
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 12 G12 Informatika student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** operators in Arduino programs — the four families that compute and decide: arithmetic, comparison, boolean and bitwise operators (Indonesia Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Arithmetic and comparison — computing and asking** — **Operators** are the symbols that work on values. The **arithmetic** family computes: `+ − * /` and the remainder `%`, building every number a sketch needs from sensor readings and constants. The **comparison** family asks: `== != < > <= >=` — each returns TRUE or FALSE, and they are the senses of every `if` the program will ever write. Indonesia's Arduino course gathers all four families into one lesson because a sketch's whole behaviour is these symbols at work; the beginner's classic fault lives here too — writing `=` (assignment) where `==` (comparison) was meant, and setting a value when they meant to ask about it.
2. **Boolean and bitwise — combining and bit-working** — The **boolean** family combines tests: `&&` (AND), `||` (OR), `!` (NOT) — the grammar of conditions with more than one sense open. The **bitwise** family works inside numbers, bit by bit: `& | ^ ~` and the shifts `<< >>` — moving and masking the single bits that are a board's flags, pin states and packed settings, where one number carries eight yes/no answers at once. The four families divide the operator world by the size of what they touch: values, tests, combinations of tests, and the bits inside the values themselves.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A symbol that works on values
2. Computes — + − * / and the remainder %
3. TRUE or FALSE — each comparison asks a question
4. Writing = (assignment) where == (comparison) was meant

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Operators in Arduino programs — the four families that compute and decide: arithmetic, comparison, boolean and bitwise operators (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of arithmetic and comparison — computing and asking as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of boolean and bitwise — combining and bit-working in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of arithmetic and comparison — computing and asking → the student studies the picture and names what each part shows
- GIF — a GIF of boolean and bitwise — combining and bit-working in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
