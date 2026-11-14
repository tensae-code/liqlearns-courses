# Lesson plan — Digital Signatures and Certificates

**Course:** Computer Science and ICT · **Title:** Safety, Security and Care · **Lesson:** Digital Signatures and Certificates
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Safety, Security and Care on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** a digital signature runs the key pair backwards — the sender locks a fingerprint of the message with their private key, and anyone can check it with the sender's public key, proving who sent it and that it was not changed — and a certificate is a trusted authority's signed statement binding a public key to a real name, so you know whose key you hold.
**This lesson's own level:** It stands on the two encryption lessons before it in Germany's strand: symmetric (one key) and asymmetric (two keys, and which direction does what).

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Signing — the pair run backwards** — A short fingerprint (hash) of the message is made; the sender encrypts that fingerprint with their private key — that is the signature. The receiver re-makes the fingerprint, decrypts the signature with the sender's public key, and compares: equal means the named sender signed it and nothing changed.
2. **Certificates — whose key is this, really?** — The gap: a public key is just a number — an attacker can publish their own key under your name. A certificate is a public key plus a name, itself signed by a trusted certificate authority (CA) whose checks bind key to identity; browsers carry CA keys and verify the chain; the attack defeated is impersonation.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Safety, Security and Care lessons Symmetric Encryption — One Shared Key and Asymmetric Encryption — Two Keys in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Walk through how a digital signature is made and checked, key by key.
2. Say the two things a valid signature proves, and the one thing it does not do.
3. Explain what a certificate is, who issues it, and the attack it defeats.

## What you need
Paper and a pencil. The worked example uses a toy 'fingerprint' — a number made from a message by a simple rule the class agrees — so every step can be done by hand.

## The run of the lesson (in order)
1. **Do it first** — A locked box keeps a message secret — but secrecy is not the only question. Who really sent this? Was a single word changed on the way? This lesson answers both, with the same two keys run in the opposite direction, and then asks the harder question hiding underneath: whose key is this, really? (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a message, its fingerprint, the fingerprint locked by a private key, and the receiver comparing two fingerprints side by side — the student walks the four pictures in order, naming the key at the locking step.
   - ADD IMAGE: a picture of a shop's certificate signed by a certificate authority, with a browser checking that signature before trusting the key — the student says what the browser refuses to do if the authority's signature fails.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a message, its fingerprint, the fingerprint locked by a private key, and the receiver comparing two fingerprints side by side → the student walks the four pictures in order, naming the key at the locking step.
- IMAGE — a picture of a shop's certificate signed by a certificate authority, with a browser checking that signature before trusting the key → the student says what the browser refuses to do if the authority's signature fails.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Signs with the public key → signatures lock with the *private* key (only the owner can make them) and are checked with the public key (anyone can check). Thinks a signed message is secret → signing proves; it does not hide. Encryption hides; it does not prove.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
