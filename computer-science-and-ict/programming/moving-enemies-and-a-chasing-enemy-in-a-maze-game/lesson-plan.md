# Lesson plan — Moving Enemies — and a Chasing Enemy — in a Maze Game

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Moving Enemies — and a Chasing Enemy — in a Maze Game
**Place in the curriculum:** ICT expansion — Finland (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Finland's *Ensiaskeleet ohjelmointiin* (student book, Oppilaan kirja, Versio 2.0), because no existing lesson teaches this thing as its own lesson.
**The one thing this lesson teaches:** A maze game's enemies move in three grades of danger: an enemy that travels back and forth between two points, an enemy that appears at random places, and the smart enemy — one that chases the player sprite itself, so standing still is never safe.
**This lesson's own level:** It stands on programming the maze's start and pointer play; the three enemy movers are built inside the lesson in rising order.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
This lesson is one whole lesson — it has no sub lessons (a short, single-skill lesson; his ruling 2026-11-09).

## Before this lesson
- Recommended first: Programming the Maze — Start, and Mouse Following in Programming. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Finland's own way is kept: this placement sits in Finland's two-part Scratch path — Part 1 moves towards the interactive-story project and Part 2 towards the self-built maze game, in the Luetaan (Let's read) then Ohjelmoidaan (Let's program) rhythm, with pair work, reflection and peer showing built in.

## What the learner can do when it ends
1. Move an enemy back and forth between two points.
2. Move an enemy to random places.
3. Make a smart enemy chase the player sprite.
4. Say how each enemy kind changes the player's danger.

## What you need
A computer with Scratch, with a maze project from the earlier lessons.

## The run of the lesson (in order)
1. **Do it first** — A maze with no enemies is a puzzle you can solve at walking pace, thinking as long as you like. The book's maze game is finished only when things in the maze move against the player. Three kinds of mover wait in this lesson — and the third one hunts. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of three maze enemies in a row — one pacing between two flags, one popping up at a question-marked random place, and one with an arrow always pointing at the player character — the student studies the picture and says, for each part of it, which part of the lesson it shows.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of three maze enemies in a row — one pacing between two flags, one popping up at a question-marked random place, and one with an arrow always pointing at the player character → the student studies the picture and says, for each part of it, which part of the lesson it shows.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Enemy drifts through walls forever → its two patrol points or random spots must lie inside the passages; place them where an enemy may legally be. Chaser is harmless → it must keep steering at the player continuously, not aim once at the start.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. For doing-lessons, the guide's assessment pattern applies: observe the doing itself, encourage pupils who lag behind and support pupils with special needs (teacher guide — evidence).
