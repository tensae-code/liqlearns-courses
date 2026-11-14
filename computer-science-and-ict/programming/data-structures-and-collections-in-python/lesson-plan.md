# Lesson plan — Data Structures and Collections in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Data Structures and Collections in Python
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** List, tuple, set and dictionary.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Four collections — list, tuple, set, dictionary** — Python builds its **collections** into the language. A **list** is ordered and changeable — the course's working collection. A **tuple** is ordered but **fixed** once made — for things that must not drift, like a point's coordinates. A **set** holds **each value once**, unordered — for membership questions ('is this pupil on the list?') where duplicates are noise. A **dictionary** holds **pairs** — a key and its value — so data is found by **name**, not position: pupil → mark, word → meaning. Four shapes, four promises; the data's job chooses among them, and Egypt's pupils meet all four in one lesson so the choice itself is the skill.
2. **Choosing and using — the collection fits the question** — Use follows the question the program must answer. 'The marks **in order**, changeable as corrections arrive' — a list. 'Has this name **already** been entered?' — a set, whose membership test is its whole point. 'The meaning **of this word**' — a dictionary, keyed lookup. The operations rhyme across the family — counting with `len`, looping over members, asking whether something is `in` — so one lesson's habits serve all four; what differs is what each **guarantees**: order, uniqueness, fixity, or naming. The book's Grade 8 placement is the point: collections are not an advanced garnish but the shape data takes in every real program these pupils will write next, from analysing an Excel file to encrypting a message.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. List, tuple, set and dictionary.
2. Ordered and changeable.
3. A list.
4. A set — its membership test is its whole point.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 8 Term 2 gives Python's collections their own lesson, a year before most courses allow them: the built-in ways Python itself holds many values together — list, tuple, set and dictionary — and how a programmer chooses among them. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of four collections — list, tuple, set, dictionary as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of choosing and using — the collection fits the question in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of four collections — list, tuple, set, dictionary → the student studies the picture and names what each part shows
- GIF — a GIF of choosing and using — the collection fits the question in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
