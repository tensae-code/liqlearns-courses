# Lesson plan — Keeping a Message Secret — Packets, TCP and Encryption Keys

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Keeping a Message Secret — Packets, TCP and Encryption Keys
**Place in the curriculum:** ICT expansion — Switzerland (2026-11-14) — in the title Networks on the ICT course ladder (TITLES.md). Built new from Switzerland's Décodage teacher guides (DEF-DGEO, canton de Vaud, French; CC BY NC SA 4.0), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building. This lesson stands on teacher-guide evidence only (Switzerland), named in its sources, counted nowhere.
**The one thing this lesson teaches:** keeping a message secret on its journey (assurer la sécurité du message): packets are carried reliably by TCP, and their contents are locked with encryption keys — and what happens if a pirate catches the key (Switzerland Grade 8 Décodage, Activité 8).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **TCP — the reliable carrier** — **TCP (Transmission Control Protocol)** is the protocol that makes packet delivery **reliable**: it numbers the packets, the receiver acknowledges what arrived, missing pieces are sent again, and the message is reassembled complete and in order. Where IP is the addressing, TCP is the promise-keeping: a message sent under TCP either arrives whole or the sender knows it did not — nothing silently vanishes.
2. **Encryption — the lock on the contents** — Reliability is not secrecy: packets can arrive whole **and** be read on the way. **Encryption** locks the contents with a **key (clef)**: intercepted packets show only scrambled data. The séance's sharp question finishes the lesson — **what if the pirate catches the key?** Then the lock opens for them too: secrecy lives and dies with the key's own safety, which is why keys are guarded, changed, and never sent alongside the message they lock.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Networks on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Switzerland's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Transmission Control Protocol
2. The packets
3. Acknowledgements of what arrived
4. They are sent again

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Your message now travels as packets through machines owned by strangers. Two fears arrive together: pieces getting lost, and pieces getting read. Before reading on, say which fear a checklist solves — and which one only a lock solves. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of tcp — the reliable carrier as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of encryption — the lock on the contents in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of tcp — the reliable carrier → the student studies the picture and names what each part shows
- GIF — a GIF of encryption — the lock on the contents in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
