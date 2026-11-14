# Lesson plan — Asynchronous, Synchronous and Isochronous Transmission

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Asynchronous, Synchronous and Isochronous Transmission
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Networks on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** bit synchronisation: the three serial timing agreements — asynchronous (start and stop bits around each character), synchronous (blocks under a shared clock) and isochronous (timed delivery for live streams) (Bangladesh HSC ICT, Chapter 2, §2.1.4).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Asynchronous — start and stop bits** — **Asynchronous transmission** sends each character in its own envelope: a **start bit** announces 'a character begins', the data bits follow, and **stop bits** close it. No shared clock runs between characters — the line may idle any length of time — so it suits irregular traffic like a keyboard's. The price is the envelope itself: extra bits on every character, a tax that grows heavy on long fast streams.
2. **Synchronous — blocks under one clock; isochronous — time itself guaranteed** — **Synchronous transmission** drops the per-character envelopes: sender and receiver share a **clock**, and data flows in large **blocks** with small control frames — the tax paid once per block, so fast bulk transfer runs efficiently. **Isochronous transmission** adds the strictest promise: bits are delivered at a **guaranteed rate with bounded delay**, because live voice and video cannot wait for late bits — a late syllable is a lost syllable. The three are one idea at three prices: agree loosely per character, agree by clock per block, or agree on time itself for streams that live or die by it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Networks on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The receiver knowing where each bit and character begins
2. A start bit and stop bits
3. Irregular traffic like a keyboard's
4. Extra bits on every character

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Serial bits arrive one after another — but how does the receiver know where one character ends and the next begins, or even when each bit starts? Sender and receiver must agree on time itself. There are three classic agreements, and this lesson walks them in order of strictness. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of asynchronous — start and stop bits as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of synchronous — blocks under one clock; isochronous — time itself guaranteed in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of asynchronous — start and stop bits → the student studies the picture and names what each part shows
- GIF — a GIF of synchronous — blocks under one clock; isochronous — time itself guaranteed in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
