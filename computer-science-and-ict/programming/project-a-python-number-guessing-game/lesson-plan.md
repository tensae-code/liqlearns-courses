# Lesson plan — Project — a Python Number-Guessing Game

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Project — a Python Number-Guessing Game
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 11 G11T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the Grade 11 unit project — designing and building a number-guessing game (and a puzzle game) in Python with IDLE (Jordan Grade 11).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Designing the game** — The design names the game's working before any code: the computer **chooses a secret** in a stated range (the random module earns its place), the player **guesses**, the program **answers** — higher, lower, or correct — and the loop **repeats until correct**, counting attempts. The design also fixes the courtesies that make it a game and not a trap: the range is told, invalid guesses are answered kindly, and the final score (attempts) is reported. Jordan's unit projects are designed on paper first, in the book's own order: the flowchart from the first lesson carries the whole game.
2. **Building it in IDLE — the unit assembled** — The build assembles the unit: **variables** hold the secret and the count, **input and conversion** take the guess, a **while loop** repeats it, **conditions** compare and answer, and the **random** choice starts each new game. The **puzzle game** companion spends the same kit differently — a shuffled word or a slid tile — proving the kit is general. The project's closing craft is testing as a player, not as the builder: play unfairly (guess outside the range, type letters) and repair what the player finds, because the player is the program's true examiner.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Choose a secret, guess, answer higher/lower/correct, repeat until correct
2. The random module
3. Attempts
4. The range is told; invalid guesses answered kindly

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The unit's lessons were pieces; the project is the whole. The computer picks a secret number; the player guesses; the computer answers higher or lower. This lesson builds it — and a puzzle game beside it — in IDLE. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of designing the game as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of building it in idle — the unit assembled in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of designing the game → the student studies the picture and names what each part shows
- GIF — a GIF of building it in idle — the unit assembled in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
