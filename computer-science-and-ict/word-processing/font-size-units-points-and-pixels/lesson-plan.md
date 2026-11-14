# Lesson plan — Font Size Units — Points and Pixels

**Course:** Computer Science and ICT · **Title:** Word Processing · **Lesson:** Font Size Units — Points and Pixels
**Place in the curriculum:** ICT expansion — Armenia (2026-11-14) — in the title Word Processing on the ICT course ladder (TITLES.md). Built new from Armenia's Digital Literacy and Computer Science books (Armenia Grade 9 G9 student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** font measurement units — the point (pt) of print and the pixel (px) of screens, and how type size is really measured (Armenia Grade 9).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The point — print's unit** — Print measures type in **points (pt)**: one point is **1/72 of an inch** (about 0.35 mm), a unit inherited from metal type. A font's size is the height of its **em** — roughly the distance from the top of its tallest letters to the bottom of its lowest descenders, not the height of any single letter, which is why two fonts at 12 pt can look different sizes. Body text in books commonly sits at 10–12 pt; Armenia's Grade 9 book teaches font measurement units (§11) inside its web-and-print block, between colour systems and operating systems.
2. **The pixel — the screen's unit, and converting between worlds** — Screens measure in **pixels (px)** — the screen's own dots. The bridge between the units: at the CSS reference density, **1 pt = 4/3 px**, so 12 pt type is 16 px — the common default body size on the web. Because real screens pack pixels at different densities, a px on a phone is not a fixed physical size; that is why web type is also set in relative units (em, rem) that scale with the reader's settings. Rule of thumb: points for print, pixels (or relatives) for screens, and never assume they match without the 4/3 bridge.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Word Processing on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Armenia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. 1/72 of an inch — about 0.35 mm
2. The height of its em — roughly tallest-top to lowest-descender, not any single letter
3. Their letters fill the em differently — the unit measures the em, not the letter you see
4. 10–12 pt

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A font size of '12' — twelve what? This lesson learns the two units type is measured in. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the point — print's unit as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the pixel — the screen's unit, and converting between worlds in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the point — print's unit → the student studies the picture and names what each part shows
- GIF — a GIF of the pixel — the screen's unit, and converting between worlds in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
