# Lesson plan — Asymmetric Encryption — Two Keys

**Course:** Computer Science and ICT · **Title:** Safety, Security and Care · **Lesson:** Asymmetric Encryption — Two Keys
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Safety, Security and Care on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** asymmetric encryption gives each person a key pair — a public key anyone may know, used to lock messages to that person, and a private key kept secret, the only key that unlocks them — so strangers can write to each other secretly without ever sharing a secret key first.
**This lesson's own level:** It stands directly on the symmetric lesson before it in Germany's strand, whose key-distribution problem this lesson solves.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The key pair — a lock anyone can close** — Each person generates a linked pair: the public key (published to the world; encrypts messages to its owner) and the private key (never shared; decrypts them). Worked flow: Ana publishes her public key; Ben encrypts with it; only Ana's private key opens the result — not even Ben can reopen it.
2. **What two keys buy — and what they cost** — The distribution problem dissolves: public keys can travel openly, private keys never travel. The cost: asymmetric operations are slow, so real systems use them to deliver a fresh symmetric key (and for signatures, next lesson), then symmetric encryption carries the data.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Safety, Security and Care lesson Symmetric Encryption — One Shared Key in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Say which key of a pair encrypts a message to someone, and which key decrypts it.
2. Explain how two strangers exchange a secret message with no shared key beforehand.
3. Say what asymmetric encryption costs (speed) and how real systems marry it to symmetric encryption.

## What you need
Paper and a pencil, and the padlock picture: an open padlock anyone can snap shut, whose only opening key never leaves its owner.

## The run of the lesson (in order)
1. **Do it first** — The last lesson ended in a circle: the shared key needs a safe road, but the safe road is what you were building. This lesson breaks the circle with an idea that sounds impossible — a lock anyone can close, that only one key in the world can open. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of open padlocks handed out to a crowd, one box snapped shut, and the single opening key staying on its owner's chain — the student points to the padlock that travels and the key that never does, and says why each is safe.
   - ADD IMAGE: a picture of a browser and a distant shop exchanging a public key openly, then a small symmetric key travelling inside the locked box — the student tells the story of the picture in order, in three sentences.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of open padlocks handed out to a crowd, one box snapped shut, and the single opening key staying on its owner's chain → the student points to the padlock that travels and the key that never does, and says why each is safe.
- IMAGE — a picture of a browser and a distant shop exchanging a public key openly, then a small symmetric key travelling inside the locked box → the student tells the story of the picture in order, in three sentences.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Encrypts with own public key to send to a friend → direction is everything: lock with the *receiver's* public key, or the receiver cannot open it. Thinks the public key must be guarded → the public key is built to be public; only the private key is guarded.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
