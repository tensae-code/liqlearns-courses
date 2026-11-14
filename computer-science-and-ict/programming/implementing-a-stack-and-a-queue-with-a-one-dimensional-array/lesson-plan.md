# Lesson plan — Implementing a Stack and a Queue with a One-Dimensional Array

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Implementing a Stack and a Queue with a One-Dimensional Array
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Building the stack and the queue on a one-dimensional array — the top pointer, the front and rear pointers, and the full/empty checks (Greece Grade 12, supplementary material Unit 1)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The stack on an array — one pointer on top** — An array of fixed size holds the pile; a pointer — **top (κορυφή)** — remembers the place of the last value pushed. **Push**: check the stack is not full (top has not reached the size), move top up one, store the value there. **Pop**: check the stack is not empty (top is not 0), take the value at top, move top down one. Every fault this structure can have lives at its two edges — pushing onto a full stack (**overflow**) and popping an empty one (**underflow**) — so the checks are not decoration; they are half the implementation.
2. **The queue on an array — two pointers, front and rear** — The queue needs **two** pointers: **front (εμπρός)** where values leave and **rear (πίσω)** where values join. Joining moves rear up and stores; leaving takes the value at front and moves front up — so the line **walks along the array** as it works, and the implementation must face the array's end honestly (the book's worked examples keep the line inside its fixed array and test full and empty by the pointers' positions). The unit works both structures through printed implementation examples step by step, pointer by pointer.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A one-dimensional array of fixed size
2. The place of the last value pushed
3. Check not full, move top up one, store the value there
4. Check not empty, take the value at top, move top down one

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The theory lesson named the stack and the queue. Greece's supplementary volume makes you build them — on the humblest structure there is, a one-dimensional array, with pointers doing the piling and the lining up. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the stack on an array — one pointer on top as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the queue on an array — two pointers, front and rear in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the stack on an array — one pointer on top → the student studies the picture and names what each part shows
- GIF — a GIF of the queue on an array — two pointers, front and rear in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
