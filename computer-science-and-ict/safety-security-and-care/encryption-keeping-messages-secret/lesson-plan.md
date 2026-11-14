# Lesson plan — Encryption — Keeping Messages Secret

**Course:** Computer Science and ICT · **Title:** Safety, Security and Care · **Lesson:** Encryption — Keeping Messages Secret
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Safety, Security and Care on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Turning a readable message into a scrambled ciphertext that reveals nothing without the secret.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Encryption — scrambling with a rule and a key** — **Encryption** turns a readable message — the **plaintext** — into a scrambled **ciphertext** that reveals nothing to a reader without the secret, using a **method** (the scrambling rule) and a **key** (the secret value the rule is worked with). **Decryption** is the journey back, possible only with the key. The separation is the whole idea: the method may be known to the world — published, taught in schoolbooks — while the key stays secret, so one method serves millions of people, each with their own key, and a message's safety rests on the key's secrecy, not on nobody knowing how scrambling works.
2. **Why it matters — and its limits** — Encryption is what lets messages cross **untrusted ground** — networks anyone can listen to — and stay private: the listener collects ciphertext and learns nothing. Egypt's pupils meet it as makers, writing a first encryption program in Python next lesson, because making a cipher teaches its limits honestly: a weak method or a short, guessable key falls to patient trying; the key must reach the receiver by some safe road of its own (the problem the course's later key lessons take up); and encryption protects the message's **content**, not its existence — watchers may still see who wrote to whom, and when. Taught this way — idea, making, limits — encryption stops being a spy word and becomes what it is: a tool with a shape, a strength and an edge.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Safety, Security and Care on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Turning a readable message into a scrambled ciphertext that reveals nothing without the secret.
2. The readable message, and its scrambled form.
3. Untrusted ground — networks anyone can listen to.
4. A weak method or guessable key falls to patient trying; the key must itself reach the receiver safely (also: content is protected, not the message's existence).

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 8 Term 2 brings its pupils to encryption through the door they have been walking toward all term — Python. Before the XOR program of the final lesson, this one teaches the idea whole: what encryption is, what a key is, and why every secret message system in history is the same three parts. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of encryption — scrambling with a rule and a key as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of why it matters — and its limits in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of encryption — scrambling with a rule and a key → the student studies the picture and names what each part shows
- GIF — a GIF of why it matters — and its limits in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
