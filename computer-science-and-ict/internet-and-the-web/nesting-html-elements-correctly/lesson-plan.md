# Lesson plan — Nesting HTML Elements Correctly

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Nesting HTML Elements Correctly
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** nesting HTML elements correctly: elements inside elements must open and close in mirror order — last opened, first closed — so the browser builds the page's tree as the writer meant it (Bangladesh HSC ICT, Chapter 4, §4.2).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Nesting — elements inside elements** — HTML pages are built by **nesting**: an element placed inside another — a paragraph inside a section, a bold word inside the paragraph, a link inside the bold. The inside element is the **child**, its container the **parent**, and the browser builds the page as exactly this tree of boxes. Nesting is how structure is said: the tree is the document's skeleton, and every later skill — styling by CSS selectors, scripting — walks this tree.
2. **The mirror rule — last opened, first closed** — The rule is one line: **elements close in the reverse order they opened** — `<p>…<b>…</b>…</p>`, never `<p>…<b>…</p>…</b>`. Wrongly nested (overlapping) tags make the browser guess where boxes end, and its guess may not be yours — the page breaks in ways that wander between browsers. The error-hunting lesson meets wrong nesting as a fault; this lesson is its prevention: write the closing tag the moment you write the opening one, then fill the middle, and the mirror can never break.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Placing an element inside another element
2. Child and parent
3. The page's tree of boxes
4. CSS styling and scripting

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Put a small box inside a big box, then try to close the big box first. Your hands refuse — the small box is in the way. HTML elements are boxes inside boxes, and they obey the same physics. This short lesson is the one rule that keeps a page's structure standing. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of nesting — elements inside elements as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the mirror rule — last opened, first closed in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of nesting — elements inside elements → the student studies the picture and names what each part shows
- GIF — a GIF of the mirror rule — last opened, first closed in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
