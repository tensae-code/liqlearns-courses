# Lesson plan — Storage Architectures

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Storage Architectures
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How stored data is arranged for organisations: storage attached to one machine, storage on the network, and storage as its own network (Greece Grade 11, Eisagogi Epistimis H/Y Ch.3.2)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Attached and networked storage — where the shelves stand** — The simplest architecture keeps storage **attached to the machine that uses it** — fast and private, but stranded when others need the same data. **Network-attached storage** puts the shelves **on the network as a named place** any authorised machine may reach, so the organisation's files live **once, together**, instead of in copies scattered per desk. The architecture question is already a sharing question: who must reach this data, and what breaks when two copies disagree?
2. **Storage as its own network — and choosing** — At the largest scale, storage becomes **its own dedicated network** behind the servers — a **storage area network** — so many servers share pools of storage at machine-room speed, and the pools can grow without the servers stopping. The chapter's judgement is by need: attached for the lone machine's speed, network-attached for the office's sharing, a storage network for the institution whose data is its life. Architecture is the database lessons' ground floor: the DBMS of the next sections stands on one of these arrangements, whether the learner names it or not.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Storage attached to the machine that uses it
2. Stranded — others cannot reach the same data
3. Shelves on the network as a named place any authorised machine may reach
4. Copies scattered per desk that disagree

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The information-systems chapter needs somewhere for its data to live. Before databases are drawn, Grade 11 arranges the shelves: the architectures by which an organisation's storage is attached, shared and grown. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of attached and networked storage — where the shelves stand as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of storage as its own network — and choosing in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of attached and networked storage — where the shelves stand → the student studies the picture and names what each part shows
- GIF — a GIF of storage as its own network — and choosing in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
