# Lesson plan — Side Effects of Subprograms

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Side Effects of Subprograms
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A subprogram's side effects: changes it makes beyond its parameters and returned value — to global variables, to files, to the screen — why they are dangerous, and how disciplined programs declare or avoid them (Moldova Grade 12, Informatică, §1.7).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What a side effect is — the uncontracted change** — A **side effect** is any change a subprogram makes **outside its contract**: altering a **global variable**, writing to a **file or the screen**, moving a device — anything besides computing its return value and its agreed (variable) parameters. The function's offence is subtle: its heading **promises** a clean exchange, so a caller reading the call sees only the exchange — the side effect is invisible exactly where decisions about it would be made. Two calls that look identical can do different amounts of hidden work.
2. **The discipline — declare, isolate, or refuse** — The chapter's discipline has three moves. **Name it**: a subprogram whose job *is* an effect (printing, saving) should be a **procedure** with the effect in its understood purpose, not a function moonlighting. **Isolate it**: pass what is needed as parameters instead of reaching for globals, so the whole influence crosses the visible border. **Refuse it** in functions: a function should compute its value from its parameters alone, so it can be used inside any expression safely — called twice, called never, without the world changing. Programs stay readable exactly as far as their effects stay visible.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A change a subprogram makes outside its contract — to globals, files, the screen — beyond its return and agreed parameters
2. The heading promises a clean exchange — the extra change is invisible at the call
3. Global variables, files, and the screen (also: devices)
4. Yes — exactly that invisibility is the danger

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 12's subprogram chapter turns detective. A subprogram is contracted to work through its parameters; some quietly work elsewhere too. Those uncontracted changes have a name, a literature of bugs, and a discipline. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of what a side effect is — the uncontracted change as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the discipline — declare, isolate, or refuse in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of what a side effect is — the uncontracted change → the student studies the picture and names what each part shows
- GIF — a GIF of the discipline — declare, isolate, or refuse in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
