# Lesson plan — Algorithm Analysis — Complexity and Computability

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Algorithm Analysis — Complexity and Computability
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The theory chapter's double question: what will this algorithm cost (complexity), and can this problem be computed at all (computability) (Greece Grade 11, Eisagogi Epistimis H/Y Ch.2.2)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Analysis and complexity — counting before running** — **Algorithm analysis** studies an algorithm's needs — **time and memory** — as the problem's size grows, without running it. Its measure is **complexity**: how the needed steps grow with the input — a growth that stays polite (following the input) against a growth that explodes (doubling with every added value, the **exponential** blow-up that makes exact answers useless even on fast machines). Analysis is the theory behind the practical rule: choose the algorithm by its growth, not by its first small test.
2. **Computability — problems no algorithm can settle** — The same chapter opens the door of **computability (υπολογισιμότητα)**: the theory of what can be computed at all. Its hard lesson: some perfectly clear problems have **no algorithm** — no procedure that always ends with the right answer — and others are computable in principle but **intractable**, their exact cost outgrowing any real machine. Knowing the boundary is part of computer science itself: it tells the programmer which problems to solve exactly, which to approximate, and which to stop attacking head-on.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An algorithm's time and memory needs as the problem's size grows — without running it
2. How the needed steps grow with the input
3. Exponential — doubling with every added value
4. By its growth, not by its first small test

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 11's theory course asks two questions most school courses never reach: not only 'how fast is this algorithm?' but 'is this problem one a computer can settle at all?' (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of analysis and complexity — counting before running as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of computability — problems no algorithm can settle in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of analysis and complexity — counting before running → the student studies the picture and names what each part shows
- GIF — a GIF of computability — problems no algorithm can settle in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
