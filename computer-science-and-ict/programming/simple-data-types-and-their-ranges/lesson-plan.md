# Lesson plan — Simple Data Types and Their Ranges

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Simple Data Types and Their Ranges
**Place in the curriculum:** ICT expansion — Armenia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Armenia's Digital Literacy and Computer Science books (Armenia Grade 10 G10 student, Armenia Grade 10 G10 teacher), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** simple data types and their ranges — the whole-number, real, character, logical and other simple types, and the limits each can hold (Armenia Grade 10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The simple types — one value, one kind** — A **simple (scalar) type** holds one value of one kind. The working family: **integer** (whole numbers), **real/floating** (numbers with a fraction), **character** (one symbol) and **string** (text), **Boolean/logical** (true or false), and in C++ the smaller and larger cousins — `short`, `long`, `float`, `double` — that trade range for memory. Armenia's Grade 10 book builds its 'Types. Composite structures' theme on them (Lesson 17): simple types first, then the composite types (array and structure) built from them.
2. **Ranges — the edges of a type, and overflow** — A type stored in a fixed number of bits has a **range**: the smallest and largest values it can hold. An 8-bit signed integer holds −128…127; add 1 to 127 and it **overflows** — wrapping to −128 or behaving wrongly, silently. Reals trade differently: a huge range, but **limited precision** — digits beyond the type's count are rounded away. Choosing a type is therefore an engineering decision: big enough for the honest largest value (with room to spare), small enough not to waste memory, and its edges written into the program's tests.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Armenia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. One value of one kind
2. Integer, real/floating, character/string, and Boolean/logical
3. Range and precision against memory — smaller types hold less, larger types hold more
4. Boolean (logical) — true and false

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every value in a program wears a type — and every type has edges. This lesson learns the simple types and where their edges are. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the simple types — one value, one kind as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of ranges — the edges of a type, and overflow in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the simple types — one value, one kind → the student studies the picture and names what each part shows
- GIF — a GIF of ranges — the edges of a type, and overflow in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
