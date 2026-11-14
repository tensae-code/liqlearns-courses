# Lesson plan — Dynamic Data Structures in C and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Dynamic Data Structures in C and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Dynamic data structures in C/C++: new and delete, pointers and their arithmetic, linked structures built at run time — the same freedom as Pascal's, with C++'s sharper edges of manual memory (Moldova Grade 12, Informatică, §5.5).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **new and delete — memory asked and returned** — C++ reserves run-time memory with **new** — `int* p = new int;` — which returns the **address** of a fresh cell, and returns it with **delete**. The pointed value is reached as **\*p**. Arrays can be born dynamic too (`new int[n]` with n known only at run time — the array whose size the program itself decides), freed by **delete[]**. Every new is a **loan**: the memory is the system's, held until delete — the contract whose breaches the next part names.
2. **The sharper edges — leaks, dangling and wild pointers** — Manual memory's three classic wounds: the **memory leak** (a pointer overwritten before delete — its cell lost for the run's whole life), the **dangling pointer** (delete done, pointer kept and followed into freed memory now possibly reused), and the **wild pointer** (never set at all, followed anywhere). Pascal fences some of this (typed pointers, no pointer arithmetic); C++ allows **pointer arithmetic** itself (p + 1 steps to the next cell) — power for arrays' innards, and rope. The elective's rule closes the pair's programming theory: **every new pairs with a delete, every pointer is nil-or-valid, and a freed pointer is set to nullptr at once**.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The address of a fresh cell
2. *p — the dereferenced pointer
3. Born with new int[n] — n decided at run time; freed with delete[]
4. A loan — the system's memory, held until delete

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The second dynamic elective crosses the pair. C++ builds the same run-time structures — with the same pointers, and with famous traps Pascal's stricter house partly fences. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of new and delete — memory asked and returned as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the sharper edges — leaks, dangling and wild pointers in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of new and delete — memory asked and returned → the student studies the picture and names what each part shows
- GIF — a GIF of the sharper edges — leaks, dangling and wild pointers in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
