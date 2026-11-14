# Lesson plan — Plotting Graphs and Diagrams in PascalABC

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Plotting Graphs and Diagrams in PascalABC
**Place in the curriculum:** ICT expansion — Belarus (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Belarus's *Інфарматыка* Grade 11, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A PascalABC program can plot: it calculates a function's values step by step and draws them as a graph on axes, and it can draw diagrams from data — so the picture is produced by the calculation, not drawn by hand.
**This lesson's own level:** It stands on the earlier lessons of its title and on the Belarus book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Plotting a function's graph** — To **plot a graph**, the program needs axes first: lines for the horizontal and vertical axes, with a chosen **scale** — how many window points stand for one unit. Then it works the function like a table: take an x value, calculate its y, turn the pair into window coordinates, and mark the point; repeat in small steps and join the points, and the **curve** appears. The program does in a blink what graph paper does in a lesson — and with another scale or another step, it does it again differently.
2. **Diagrams from data** — A **diagram** shows amounts, not a function: the program reads the data values and draws each as a bar or sector of the height or size the value deserves, in the same scale across the whole diagram — the comparison is the message. Both graph and diagram share one discipline: the picture must be **honest to the numbers** — axes and scales stated, steps even, heights proportional — because a plotted picture persuades faster than a table, and a wrong scale persuades wrongly. That is why this section closes the graphics work: pictures from programs are claims, and the programmer answers for them.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Belarus's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The axes, with a chosen scale.
2. By calculating y for step-by-step x values, marking each point, and joining the points.
3. Honesty to the numbers — stated axes and scales, even steps, proportional heights.
4. Yes — change the scale and re-run.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Plotting a graph by hand takes a page of calculations and a careful hand. A program does the same work in a blink — for any function, any scale. In this lesson your PascalABC programs plot graphs from functions and diagrams from data. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of axes with a stated scale and a curve being plotted point by point across them — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of a row of bars of different heights with one scale ruler standing beside them — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of axes with a stated scale and a curve being plotted point by point across them → the student studies the picture and names what each part shows
- GIF — a GIF of a row of bars of different heights with one scale ruler standing beside them → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
