# Lesson plan — Blockchain — Trusted Digital Records

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Blockchain — Trusted Digital Records
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A blockchain is a shared record book kept as a chain of blocks — each block holds records plus a fingerprint (hash) of the block before it — copied onto many computers at once, so changing an old record would break the chain and be seen by everyone: records that no single keeper can quietly rewrite.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Blocks, hashes and the chain** — Records are packed into **blocks**. Each block carries a **hash** — a short fingerprint computed from its contents — and the **hash of the previous block**, linking them into a **chain**. Alter any old record and its block's hash changes, which no longer matches the link stored in the next block: the tampering shows. New blocks are added by agreed rules, never by editing old ones.
2. **Many copies, no single keeper** — The chain is **distributed**: many computers hold a full copy and compare notes, so there is no single keeper to bribe, hack or lose the book. That is the trust idea in the book's title — **trusted digital records**: trust comes from the structure, not from trusting a person. The famous use is cryptocurrency, but the same structure serves land records, certificates and supply chains.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Records, its own hash and the previous block's hash.
2. Its hash changes and the chain link breaks — the tampering shows.
3. Many computers each hold a full copy of the chain.
4. From the structure, not from a trusted person.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A record one person keeps can be quietly changed by that person. This lesson is about a record book designed so that nobody can quietly change anything. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of blocks, hashes and the chain as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of many copies, no single keeper in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of blocks, hashes and the chain → the student studies the picture and names what each part shows
- GIF — a GIF of many copies, no single keeper in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
