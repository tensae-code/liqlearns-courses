# Lesson plan — Dynamic Data Structures in Pascal

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Dynamic Data Structures in Pascal
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Dynamic data structures in Pascal: data whose size is decided at run time — pointers, linked lists built node by node with new and dispose, against the fixed sizes of arrays and records (Moldova Grade 12, Informatică, §5.4).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Pointers — variables that hold addresses** — A **pointer** is a variable that holds not a value but the **address of a value** in memory: `var p: ^integer;` declares a pointer to an integer. The operations are a small new alphabet: **new(p)** reserves a fresh cell and sets p to its address; **p^** names the value at the address (the pointer **dereferenced**); **dispose(p)** frees the cell; **nil** is the pointer that points nowhere — the honest empty. A variable made by new has **no name of its own**: it is reached only through its pointer, which is the structure's whole new power and danger.
2. **Linked lists — structure built at run time** — A **linked list** chains **nodes** — records holding a value and a **pointer to the next node** — ending at nil. It **grows by one new per inserted node and shrinks by dispose**, needing exactly the memory its data needs, where an array wastes its declared size or overflows it. Its prices are the duals of its gifts: no index (the fifth node is reached by **walking** four links), and the programmer now owns memory's housekeeping — a lost pointer **leaks** its cell, a followed disposed pointer **crashes**. Dynamic structures trade the compiler's guard for the programmer's freedom, knowingly.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The address of a value in memory, not the value
2. new reserves a fresh cell and points at it; dispose frees the cell
3. The value at the pointer's address — the dereferenced pointer
4. The pointer that points nowhere — the honest empty

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every structure so far declared its size before it ran. The first Grade 12 programming elective removes that limit: structures that grow and shrink while the program runs, built from pointers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of pointers — variables that hold addresses as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of linked lists — structure built at run time in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of pointers — variables that hold addresses → the student studies the picture and names what each part shows
- GIF — a GIF of linked lists — structure built at run time in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
