# Lesson plan — Encrypting Messages with XOR in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Encrypting Messages with XOR in Python
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** 1 when the two bits differ, 0 when they are the same.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **XOR — the operation that undoes itself** — **XOR** compares two bits and answers 1 when they **differ**, 0 when they are the **same**: 0⊕0=0, 0⊕1=1, 1⊕0=1, 1⊕1=0. Applied to a whole character's bits against a key's bits, it scrambles. The accident that makes the lesson: **XOR with the same key twice returns the original** — because each bit is flipped, then flipped back. So one operation is both encryptor and decryptor: ciphertext = plaintext ⊕ key, and plaintext = ciphertext ⊕ key. No separate decryption method exists to invent, carry or lose — the same line of code, run on the ciphertext with the same key, gives the message back.
2. **The program — characters, codes, a key, a loop** — The book's program assembles the term: each **character** of the message is taken in a **loop**, turned into its **code number**, XORed with the **key** number, and the results gathered — as numbers, or turned back into characters — into the ciphertext. Decryption is the identical program fed the ciphertext. The teaching then turns critic, as Egypt's course keeps doing: this cipher is a perfect **teaching** cipher and a weak **real** one — a single short key repeats its pattern across a long message, and patterns are what codebreakers eat. The pupil who can say both things — how it works, and why the real world needs more — has learned the lesson the book placed last on purpose.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. 1 when the two bits differ, 0 when they are the same.
2. 0 — the bits are the same.
3. Takes it in a loop, turns it into its code number, XORs it with the key.
4. The XORed results — as numbers, or turned back into characters.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The final lesson of Egypt's Grade 8 Term 2 is a program: encryption using the XOR operation, in Python. It is a small masterpiece of placement — the term's Python (conditions, loops, functions, collections) and its encryption idea meet in one short program whose secret is a beautiful arithmetical accident. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of xor — the operation that undoes itself as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the program — characters, codes, a key, a loop in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of xor — the operation that undoes itself → the student studies the picture and names what each part shows
- GIF — a GIF of the program — characters, codes, a key, a loop in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
