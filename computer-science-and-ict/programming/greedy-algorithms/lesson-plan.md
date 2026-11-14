# Lesson plan — Greedy Algorithms

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Greedy Algorithms
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 11 G11 Informatika student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** greedy algorithms — solving a problem by taking the best-looking step at every moment, and knowing the problems where that hunger is exactly right (Indonesia Grade 11).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Take the best now — the greedy choice** — A **greedy algorithm** (algoritma greedy) builds its answer in steps and, at each step, takes the **locally best** choice — the largest coin, the earliest-finishing activity, the nearest city — never looking back and never reconsidering. Indonesia's Grade 11 chapter teaches it between recursion and dynamic programming as the fastest of the three tempers: where it works, it is beautifully simple — no table, no backtracking, just a rule for 'best now' applied until the answer stands. Coin change with the right coin system is its school example: always take the largest coin that fits, and the fewest coins result.
2. **When hunger fails — the greedy test** — Greedy's speed is bought with a risk: the best now can poison the whole — a coin system of 1, 3 and 4 making 6 greedily takes 4+1+1 (three coins) where 3+3 (two) was waiting. So the chapter's real skill is the **greedy test**: before trusting hunger, ask whether a locally best choice can ever block a globally best answer — some problems are built so it cannot (their choices never close a needed door), and for those, greedy is not a gamble but a proof. Name the temper, test the problem, then let it run.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Takes the locally best choice — and never looks back or reconsiders
2. The largest coin, the earliest-finishing activity, the nearest city
3. No table and no backtracking — just a rule for 'best now'
4. Coin change — always take the largest coin that fits

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Greedy algorithms — solving a problem by taking the best-looking step at every moment, and knowing the problems where that hunger is exactly right (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of take the best now — the greedy choice as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of when hunger fails — the greedy test in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of take the best now — the greedy choice → the student studies the picture and names what each part shows
- GIF — a GIF of when hunger fails — the greedy test in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
