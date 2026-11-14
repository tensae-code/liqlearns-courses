# Lesson plan — Backtracking

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Backtracking
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 11 Chuyên đề Tin học 11 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** backtracking — building a solution step by step and, the moment a partial build fails, stepping back and trying the next choice, until a full solution stands or every road is proven closed (Vietnam Grade 11 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Build, test, step back — the technique** — **Backtracking** (duyệt quay lui) improves exhaustive search with one idea: build the answer **step by step**, and test each **partial** build at once. The moment a partial build **cannot** lead to a solution, abandon it — **backtrack** to the last choice point and try the **next choice** — without building the whole doomed family beneath it. Where plain exhaustive search generates every candidate whole, backtracking prunes whole branches with one early failure, which is why hard placement problems (queens, routes, timetables) yield to it.
2. **Designing with backtracking — choices, conditions, recursion** — A backtracking program has a fixed shape: a **recursive** procedure that places the next piece, with the **choices** at each step listed, the problem's **conditions** checked after every placement, and the **return** from the call doing the stepping back. Vietnam's specialist book teaches the design, then drills it twice — a technique practical and a design practical — because the shape transfers: change the pieces, the choices and the conditions, and the same skeleton solves the next problem.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Build step by step, test each partial build, and abandon a failing one at once
2. Backtrack — return to the last choice point and try the next choice
3. It prunes whole branches with one early failure instead of generating every candidate whole
4. Hard placement problems — queens, routes, timetables

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — backtracking — building a solution step by step and, the moment a partial build fails, stepping back and trying the next choice, until a full solution stands or every road is proven closed (Vietnam Grade 11 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of build, test, step back — the technique as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of designing with backtracking — choices, conditions, recursion in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of build, test, step back — the technique → the student studies the picture and names what each part shows
- GIF — a GIF of designing with backtracking — choices, conditions, recursion in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
