# Lesson plan — Finding Errors in HTML

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Finding Errors in HTML
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to detect errors in HTML — the common faults (unclosed tags, wrong nesting, misspelled tag names, missing quotes) and the habit of checking the page against the code
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The common faults** — Most beginner HTML errors are one of four: an **unclosed tag** (a <b> or <p> with no closing tag, so its effect runs to the page's end); **wrong nesting** (tags closed in the wrong order — <b><i>text</b></i> instead of <b><i>text</i></b>); a **misspelled tag or attribute name**, which the browser silently ignores; and **missing quotes** around an attribute value, which breaks the attribute. Browsers rarely complain — they guess and carry on — so the page, not an error message, is the evidence.
2. **The checking habit — page against code** — Finding the fault is a **comparison**: look at what the page **shows**, name exactly what is wrong and where it starts, then read the code **from that place** for the four faults. The fault is almost always at or just before the place where the wrongness starts — a heading that never ends began at its unclosed tag. Malaysia's method is to fix **one fault at a time** and re-open the page after each fix, so every change's effect is seen on its own; guessing in batches hides which fix worked.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An unclosed tag — its effect runs to the page's end
2. Tags closed in the wrong order — </b> before </i> when <i> opened last
3. Nothing visible — the browser silently ignores it
4. A comparison — what the page shows against the code

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The page looks wrong: a heading swallows the whole page, a link does nothing. Malaysia's Grade 7 HTML unit ends by teaching learners to hunt the fault in the code. In this lesson you learn the common HTML errors — and the checking habit that finds them. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the common faults as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the checking habit — page against code in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the common faults → the student studies the picture and names what each part shows
- GIF — a GIF of the checking habit — page against code in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
