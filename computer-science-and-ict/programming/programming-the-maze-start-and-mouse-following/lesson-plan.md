# Lesson plan — Programming the Maze — Start, and Mouse Following

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Programming the Maze — Start, and Mouse Following
**Place in the curriculum:** ICT expansion — Finland (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Finland's *Ensiaskeleet ohjelmointiin* (student book, Oppilaan kirja, Versio 2.0), because no existing lesson teaches this thing as its own lesson.
**The one thing this lesson teaches:** A maze game starts in a known state — the character sent to its start position and the stage switched to Maze 1 every time the green flag is clicked — and then plays by the mouse: the character waits for the pointer, follows it, ends the game if it touches a wall, and changes the level when it touches the goal.
**This lesson's own level:** It stands on drawing the maze levels and on coordinates, events and touching tests; the start routine and the follow-the-pointer play are built inside the lesson in order.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The start situation — always the same beginning** — Program the start situation on the green flag.
2. **Follow the pointer — walls end, goal advances** — Make the character follow the pointer with wall and goal tests.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Drawing Maze Levels as Backdrops — One Wall Colour in Programming. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Finland's own way is kept: this placement sits in Finland's two-part Scratch path — Part 1 moves towards the interactive-story project and Part 2 towards the self-built maze game, in the Luetaan (Let's read) then Ohjelmoidaan (Let's program) rhythm, with pair work, reflection and peer showing built in.

## What the learner can do when it ends
1. Program the start situation: character to its start position, stage to Maze 1, on the green flag.
2. Make the character wait for the mouse pointer, then follow it.
3. End the game when the character touches a wall.
4. Change the level when the character touches the goal.

## What you need
A computer with Scratch, with a maze project from the earlier lessons.

## The run of the lesson (in order)
1. **Do it first** — Press the green flag twice on a half-built game: once the character starts where it finished last time, somewhere mid-maze. A real game must begin identically every single run. And once it begins, the player — holding only a mouse — must be able to steer without ever touching a wall. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a maze game at the flag click: the character jumping back to Maze 1's entrance and the backdrop switching to Maze 1, with a circular reset arrow over the scene — the student studies the picture and says, for each part of it, which part of the lesson it shows.
   - ADD IMAGE: a picture of a small character following a mouse pointer through maze passages, a wall glowing where a touch would end the game, and the goal at the end switching the stage to the next maze — the student studies the picture and says, for each part of it, which part of the lesson it shows.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a maze game at the flag click: the character jumping back to Maze 1's entrance and the backdrop switching to Maze 1, with a circular reset arrow over the scene → the student studies the picture and says, for each part of it, which part of the lesson it shows.
- IMAGE — a picture of a small character following a mouse pointer through maze passages, a wall glowing where a touch would end the game, and the goal at the end switching the stage to the next maze → the student studies the picture and says, for each part of it, which part of the lesson it shows.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Game starts mid-maze → the start routine is missing a piece: check both go-to-start and switch-to-Maze-1 under the flag. Character never waits → it follows before the pointer arrives; the wait comes first. Walls do not end the game → the touching test must use the one wall colour, checking while following, not once.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. For doing-lessons, the guide's assessment pattern applies: observe the doing itself, encourage pupils who lag behind and support pupils with special needs (teacher guide — evidence).
