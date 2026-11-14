# Lesson plan — Strings in C — Character Arrays and the Null Character

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Strings in C — Character Arrays and the Null Character
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** strings in C: text held as an array of characters, ended by the null character '\0' — worked through the book's own storage table for the word 'Bangla' (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **A string is a char array — the 'Bangla' table** — In C, a **string** is an **array of char**: `char word[10];` holds a row of characters, each in its numbered room, reached by the array's indexing. The book lays the word **'Bangla'** out in its storage table — B in room 0, a in 1, n in 2, and so on — because a C string is nothing more mystical than this: letters in rooms, in order. Declared with a literal, `char country[] = "Bangla";`, the compiler builds the row for you — and quietly adds one more room, for the character of the next part.
2. **The null character — where the string ends** — Every C string ends with the **null character, '\0'** — a character whose code is **zero**, invisible, unprintable, and load-bearing: it is how every C string function knows **where the text stops**. 'Bangla' occupies **seven rooms, not six** — six letters and the terminator. An array sized exactly for its letters has **no room for '\0'** and is not yet a string — functions reading it march past its end into foreign memory, the array lesson's edge fault in its most famous form. Size for the terminator, always: letters + 1.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An array of char
2. In room 0
3. The compiler
4. One character

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Python hands you a string type. C — the mid-level language that hides nothing — hands you an array and a promise: characters in a row, and one special invisible character standing at the end saying 'the text stops here'. Forget the promise and C's strings misbehave in ways this lesson exists to prevent. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a string is a char array — the 'bangla' table as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the null character — where the string ends in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a string is a char array — the 'bangla' table → the student studies the picture and names what each part shows
- GIF — a GIF of the null character — where the string ends in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
