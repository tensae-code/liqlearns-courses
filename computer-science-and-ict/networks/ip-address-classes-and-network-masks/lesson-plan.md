# Lesson plan — IP address classes and network masks

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** IP address classes and network masks
**Place in the curriculum:** Title — Networks in the Computer Science and ICT ladder (TITLES.md); stocked from Ethiopia's Grade 10 book, Unit 2 — Computer Network. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** The **first octet** sorts IPv4 into classes **A (0–127), B (128–191), C (192–223), D (224–239), E (240–255)** — and a **network mask** splits network from node.
**This lesson's own level:** it stands on IP addresses — the learner can read an address; this lesson sorts it and splits it.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Five classes by first octet** — the five ranges; A/B/C host classes; D multicast; E experimental
2. **Network masks — network from node** — the mask's job; the three default masks; class by range and by leading bits

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: IP addresses — IPv4 and IPv6. Recommended, never forced.

## What the learner can do when it ends
1. Give all five classes' first-octet ranges.
2. Say which classes serve as host addresses and what D and E are for.
3. State the three default masks and find an address's class two ways.

## What you need
Paper and a pencil; a networked computer for the book's practical, if available.

## The run of the lesson (in order)
1. **Do it first** — Take three addresses and look only at the first number of each. That first number alone tells each address's class — its family, its size, its mask. Learn the five families. (lesson/lesson.md).
2. **The explanation** — the parts in lesson/lesson.md, in order.
   - ADD IMAGE [Picture 14538]: a picture of a five-row class chart with first-octet ranges, network/host split bars and default masks — the student finds a given address's row and reads its split and mask.
   - ADD AUDIO: a voice reading the lesson's key words and its one-thing sentence aloud — the student listens and repeats each key word.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 14538] — the five-row class chart → the student finds an address's class, split and mask.
- AUDIO — the lesson's key words read aloud → the student listens and repeats.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Ranges in order: A ends 127, B ends 191, C ends 223, D ends 239, E ends 255. The mask's 255s cover the network part — count the 255s and you have the network octets.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 10 Information Technology, Unit 2 — Computer Network). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
