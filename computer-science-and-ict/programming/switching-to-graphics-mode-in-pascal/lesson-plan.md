# Lesson plan — Switching to Graphics Mode in Pascal

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Switching to Graphics Mode in Pascal
**Place in the curriculum:** ICT expansion — Uzbekistan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Uzbekistan's informatics student books (Russian-language editions), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Graphics work begins with the **Graph unit** named in **uses**, and the call **InitGraph**, which loads the graphics driver and switches the screen from text mode to **graphics mode** — a grid of points the program can light one by one.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **InitGraph — entering graphics mode** — Graphics work begins with the **Graph unit** named in **uses**, and the call **InitGraph**, which loads the graphics driver and switches the screen from text mode to **graphics mode** — a grid of points the program can light one by one. Until InitGraph runs, the drawing operators have no canvas; the book gives the switch its own lesson before any figure is drawn.
2. **Coordinates and CloseGraph** — In graphics mode every point has **coordinates**: x grows to the right, y grows **downward** from the top-left corner — the opposite of the maths graph, and the cause of most first mistakes. Work ends with **CloseGraph**, which returns the screen to text mode. Open the mode once, draw everything, close it once: that frame holds every graphics program in the course.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Uzbekistan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The Graph unit.
2. Loads the graphics driver and switches the screen to graphics mode.
3. The top-left corner.
4. Downward.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Before Pascal can draw a single point, the screen must change its mode: from text to graphics. Grade 9's lesson is that switch — InitGraph, the Graph unit, and closing the mode properly. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of initgraph — entering graphics mode as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of coordinates and closegraph in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of initgraph — entering graphics mode → the student studies the picture and names what each part shows
- GIF — a GIF of coordinates and closegraph in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
