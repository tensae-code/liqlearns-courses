# Lesson plan — Symmetric Encryption — One Shared Key

**Course:** Computer Science and ICT · **Title:** Safety, Security and Care · **Lesson:** Symmetric Encryption — One Shared Key
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Safety, Security and Care on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** symmetric encryption locks and unlocks a message with one and the same key: sender and receiver must both hold that shared secret key before anything travels — the method is fast, but getting the key to both sides without it being stolen is its famous problem.
**This lesson's own level:** It stands on the coding strand before it — a cipher is a code with a secret rule — and on ordinary locks: one key that both locks and unlocks the same padlock.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **One key, both ways — the shift cipher at work** — Plaintext, key, ciphertext; the Caesar shift as the working example (shift by the key number, wrap around the alphabet); encrypt and decrypt as the same key run forwards and backwards; a modern symmetric cipher named (AES) doing the same job at machine scale.
2. **The catch — getting the key there** — Key distribution: both sides need the same key before the first message, but sending the key needs a channel that is already safe — the circle at the heart of symmetric encryption; where symmetric still wins (speed, bulk data) and how real systems pair it with the asymmetric fix taught next.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lessons on coding in this course (Representing Information Through Coding; Bits, Bytes and Number Systems). Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Encrypt and decrypt a short message with a simple shift (Caesar) key.
2. Say what makes an encryption symmetric, and name its great strength.
3. Explain the key-distribution problem in your own words.

## What you need
Paper and a pencil, and two copies of the alphabet written in a strip — a paper wheel or two sliding strips makes the shift cipher physical.

## The run of the lesson (in order)
1. **Do it first** — Write a note you would not want the class to read, and pass it across the room. Anyone who catches it can read it. This lesson shows the oldest fix — scramble it with a key — and the catch that has followed that fix for two thousand years. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two alphabet rings, the inner turned by three, with H pointing to K — the student encrypts the first letter of their own name with the same key, using the rings.
   - ADD IMAGE: a picture of two people holding copies of one padlock key, with a watcher on the road the spare key must travel — the student says in one sentence why that road is the whole problem.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two alphabet rings, the inner turned by three, with H pointing to K → the student encrypts the first letter of their own name with the same key, using the rings.
- IMAGE — a picture of two people holding copies of one padlock key, with a watcher on the road the spare key must travel → the student says in one sentence why that road is the whole problem.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks the cipher method is the secret → the method is public (Caesar's shift is 2,000 years famous); the key alone is secret, and changing keys is cheap while changing methods is not. Encrypts letter by letter with different shifts and calls it one key → one key means one rule for the whole message.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
