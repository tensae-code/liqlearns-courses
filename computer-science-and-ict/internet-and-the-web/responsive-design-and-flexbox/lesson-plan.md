# Lesson plan — Responsive Design and Flexbox

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Responsive Design and Flexbox
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A modern page must fit every screen: Flexbox lays elements out in flexible rows and columns that stretch, shrink and wrap by themselves, and media queries inside the CSS change the layout when the screen is narrow — together they make one page that is right on a phone and on a wide monitor.
**This lesson's own level:** It stands on the CSS lesson (selectors and rules) and on the box model lesson. A learner who can write a simple CSS rule can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Flexbox — laying out with flexible boxes** — A container becomes a flex container; its children line up along a main axis, stretch or shrink to share the space, align across the other axis, and wrap onto new lines when they no longer fit — the layout adapts by itself instead of being fixed pixel by pixel.
2. **Media queries — one page, many screens** — A media query asks the screen a question — how wide are you? — and applies its CSS rules only when the answer matches; with a breakpoint, the same page shows three boxes across on a wide screen and one column on a phone.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Internet and the Web lessons on CSS and on the CSS box model, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Le Web", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Turn a container into a flex container and make its boxes share the space in a row.
2. Make flex boxes wrap onto new lines when the screen narrows.
3. Write a media query with a breakpoint that changes the layout for narrow screens.
4. Explain why one responsive page is better than a separate mobile site.

## What you need
A computer with a text editor and a browser, to try the layouts. Paper works for the planning parts.

## The run of the lesson (in order)
1. **Do it first** — Open any page you know on a wide screen and imagine it squeezed into a phone — note what breaks — before the lesson shows the two tools that fix it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of three boxes in a flex row on a wide screen and the same boxes wrapped onto two lines on a narrow screen — the student points at where the wrap happened and says what allowed it
   - ADD GIF: a GIF of a browser window being dragged narrower while flex boxes rearrange themselves smoothly — the student narrates what each box does as the window shrinks
   - ADD IMAGE: a picture of the same page wide and narrow with the media query written underneath — the student finds the breakpoint in the code and says which rules apply below it
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of three boxes in a flex row on a wide screen and the same boxes wrapped onto two lines on a narrow screen → the student points at where the wrap happened and says what allowed it
- GIF — a GIF of a browser window being dragged narrower while flex boxes rearrange themselves smoothly → the student narrates what each box does as the window shrinks
- IMAGE — a picture of the same page wide and narrow with the media query written underneath → the student finds the breakpoint in the code and says which rules apply below it
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Boxes refuse to share space → the grow values live on the children, the flex declaration on the parent; check which element carries which. Media query never applies → check the breakpoint direction (max-width means "this width and below") and that the query comes after the normal rules it must override. Boxes overflow instead of wrapping → wrapping is off by default; it must be switched on.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France's SNT book teaches this in the Prolongements of its Web theme, after the CSS Cours — this lesson keeps that place, as the step after the box model.
