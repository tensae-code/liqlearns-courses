# Lesson plan — Encryption and RSA Public-Key Cryptography

**Course:** Computer Science and ICT · **Title:** Safety, Security and Care · **Lesson:** Encryption and RSA Public-Key Cryptography
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Safety, Security and Care on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 2*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Encryption scrambles a message with a key so only the holder of the right key can read it; RSA is the famous public-key method — each person publishes a public key that locks messages, and keeps a private key that alone can unlock them — and its lock works because multiplying two large primes is easy while undoing the multiplication is, in practice, impossible.
**This lesson's own level:** It stands on the security lessons (what security means, passwords) and on basic multiplication and remainders from school mathematics. The numbers in this lesson are kept tiny so the whole working of RSA can be seen by hand.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Encryption and keys** — **Encryption** turns readable text — **plaintext** — into scrambled **ciphertext**, using a **key**: a secret value that steers the scrambling. The receiver uses a key to turn the ciphertext back into plaintext. In **symmetric** encryption one shared key both locks and unlocks, which raises a hard question: how do two people agree that key without an eavesdropper hearing it too? **Asymmetric**, or public-key, encryption answers it by splitting the key in two: a **public key**, shared with the whole world, that only locks; and a **private key**, never shared, that alone unlocks. Anyone can lock a message to you; only you can open it.
2. **RSA — how the two keys work** — RSA builds the key pair from two large **prime numbers**, multiplied together. The public key carries the product; the private key is worked out from the primes themselves. Locking a message means doing arithmetic with the product; unlocking needs the primes — and finding them again from the product alone means factoring an enormous number, which no known method can do in useful time. That one-way street is the whole secret: easy to multiply, practically impossible to un-multiply. The book's practical implements RSA in Python with small primes, so the student watches a message become numbers, get locked with a public key, and open again only with the private one.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Say what plaintext, ciphertext and a key are.
2. Say how symmetric encryption differs from public-key encryption, and what hard question the public key answers.
3. Explain RSA's one-way street: primes multiply easily; the product cannot be factored back in useful time.
4. Follow a small-numbers RSA locking and unlocking, naming what the public and private keys each know.

## What you need
Paper and a pencil. A computer with Python for the book's RSA practical, if available.

## The run of the lesson (in order)
1. **Do it first** — Write a secret on paper and pass it across the classroom: everyone in between can read it. Now imagine the paper scrambles itself for everyone except the one friend it is meant for — even though the 'lock' you used is one you happily shout to the whole class. That impossible-sounding trick exists. It is RSA, and in this lesson you do it with real numbers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two keys on a table — one labelled PUBLIC being handed out to a crowd, one labelled PRIVATE going into its owner's pocket — with a padlock snapping shut under the public key and opening only under the private one — the student points at the key that locks and the key that unlocks.
   - ADD GIF: a GIF of two small primes, 5 and 11, multiplying into 55 with a padlock closing — then a crowd of guesses failing to split 55 back apart before the owner's private key opens it — the student watches once, then says what the private key knows that the public key does not.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two keys on a table — one labelled PUBLIC being handed out to a crowd, one labelled PRIVATE going into its owner's pocket — with a padlock snapping shut under the public key and opening only under the private one → the student points at the key that locks and the key that unlocks
- GIF — a GIF of two small primes, 5 and 11, multiplying into 55 with a padlock closing — then a crowd of guesses failing to split 55 back apart before the owner's private key opens it → the student watches once, then says what the private key knows that the public key does not
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks the public key must also be kept secret → the public key only locks; it can be shouted to the world. The danger sits in the private key alone. Thinks RSA is safe because nobody knows the method → the method is published; the safety is the factoring problem, not secrecy of the recipe. Mixes up which key does what → public locks, private unlocks (say it as: publish the padlock, keep the key).

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
