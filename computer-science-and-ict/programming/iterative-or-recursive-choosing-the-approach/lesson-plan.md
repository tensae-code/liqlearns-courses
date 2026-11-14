# Lesson plan — Iterative or Recursive — Choosing the Approach

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Iterative or Recursive — Choosing the Approach
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The same problem, two engines: iteration (a loop with explicit state) against recursion (a subprogram calling itself) — their costs in time and memory, and the judgement that chooses between them (Moldova Grade 12, Informatică, §2.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The two engines — state kept by hand, or by the call stack** — An **iterative** solution drives its work with a **loop and explicit variables**: the programmer keeps the state, step by visible step. A **recursive** solution lets a subprogram **call itself** on a smaller part, the state kept implicitly in the **chain of calls** — each call's own variables waiting on the stack until its inner call returns. The recursion reads as the problem's own definition (factorial, tree walks, divide-and-conquer); the iteration shows its machinery. Same answers — different bookkeeping.
2. **Costs and the choice — stack depth against clarity** — Recursion pays in **memory**: every pending call holds a stack frame, so a recursion as deep as its input (a million-deep factorial) can **overflow the stack**, while iteration's variables are a fixed few. Recursion often pays also in repeated work when subcalls overlap (the naive Fibonacci computes the same values exponentially often) — unless its structure is a true division with no overlap. The chapter's rule: **recurse where the problem is self-similar and division is clean and depth is modest; iterate where depth is huge, overlap would repeat work, or the loop is simply plain**. Judge by the structure, not by fashion.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Explicitly — in variables the programmer manages, step by step
2. Implicitly — in the chain of calls, each call's variables waiting on the stack
3. Where the problem defines itself — factorial, tree walks, divide-and-conquer
4. Its machinery — the state and step order in the open

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 12's complexity chapter asks its practical question. Almost every recursive solution has an iterative twin and vice versa; the craft is not in writing either, but in knowing what each will cost. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the two engines — state kept by hand, or by the call stack as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of costs and the choice — stack depth against clarity in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the two engines — state kept by hand, or by the call stack → the student studies the picture and names what each part shows
- GIF — a GIF of costs and the choice — stack depth against clarity in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
