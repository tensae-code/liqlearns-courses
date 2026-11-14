# Lesson plan — Finding a Winning Strategy — The Game of Nim

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Finding a Winning Strategy — The Game of Nim
**Place in the curriculum:** ICT expansion — Switzerland (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Switzerland's Décodage teacher guides (DEF-DGEO, canton de Vaud, French; CC BY NC SA 4.0), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building. This lesson stands on teacher-guide evidence only (Switzerland), named in its sources, counted nowhere.
**The one thing this lesson teaches:** finding a winning strategy for the game of Nim (comment gagner au jeu de Nim?): analysing a take-away game backwards until a strategy that always wins stands revealed (Switzerland Grade 6 Décodage, Enquête 4, and the Grade 8 studio game).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Positions that win and positions that lose** — The inquiry's method is **backward analysis**: start from the end. Facing 1, 2 or 3 matches you win at once; facing 4 you lose against perfect play (whatever you take, the opponent takes the rest); so 4 is a **losing position** — and every multiple of 4 is, because the opponent can always answer your take of k by taking 4−k. Positions sort into winning and losing, and the whole game collapses into knowing which is which.
2. **A strategy that always works** — A **winning strategy** is the analysis turned into conduct: always leave a losing position; from any other position, move to one. The Grade 8 studios meet Nim again as a **video-game project in expert mode** — the algorithm of the unbeatable opponent is this strategy, coded. The inquiry's deeper prize is the shape of the thinking: some games are **solved** — not played better, but understood completely — and the solving method (work backwards from the end) returns in mathematics and programming wherever a perfect plan is hunted.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Switzerland's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. From the end — backwards
2. Whatever you take, the opponent takes the rest
3. Every multiple of 4
4. By taking 4−k, restoring the multiple of 4

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Fifteen matches. Two players take 1, 2 or 3 at a time; who takes the last match wins. Play it twice in your head against a perfect opponent. Before reading on: is this a game of luck, of speed — or of something colder? (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of positions that win and positions that lose as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of a strategy that always works in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of positions that win and positions that lose → the student studies the picture and names what each part shows
- GIF — a GIF of a strategy that always works in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
