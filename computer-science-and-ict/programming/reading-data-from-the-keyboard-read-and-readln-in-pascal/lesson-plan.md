# Lesson plan — Reading Data from the Keyboard — read and readln in Pascal

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Reading Data from the Keyboard — read and readln in Pascal
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How a Pascal program takes data in: read and readln (and C++'s cin) fill variables from the keyboard, readln finishing the line — the input half of every interactive program (Moldova Grade 8 §3.8 and Grade 10 §3.9).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **read and readln — filling variables from the keyboard** — **read** takes the next values typed at the keyboard and stores them into the variables named in its brackets: `read(a, b)` waits, takes two values and places them. **readln** does the same and then **skips to the end of the input line**, discarding whatever else was typed on it — the safer default for line-by-line data. When a read executes, the program **waits**: execution pauses until the user types and presses Enter. C++ reads with `cin >>`.
2. **The conversation — prompt, read, echo** — Interactive programs follow a courtesy protocol this section makes explicit: **prompt first** (writeln what you ask for — the user cannot guess), **read second**, **echo or use third** (show what was taken, so mistyping is caught at once). Numbers are typed separated by spaces or Enter; characters read raw, one by one, including spaces — so reading a name with readln into a string differs from reading numbers. Input is a contract: the program states the order and kinds it expects, the user supplies exactly those.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It waits for two typed values and stores them into a and b
2. It skips to the end of the input line, discarding the rest of that line
3. It waits — execution pauses until the user types and presses Enter
4. cin >>

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Programs that only print are monologues. Grade 8 and Grade 10 teach the listening half in the same place in both books: read and readln, the instructions that let the user answer. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of read and readln — filling variables from the keyboard as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the conversation — prompt, read, echo in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of read and readln — filling variables from the keyboard → the student studies the picture and names what each part shows
- GIF — a GIF of the conversation — prompt, read, echo in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
