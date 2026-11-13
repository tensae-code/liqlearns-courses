# Lesson plan — XOR and XNOR gates — from basic gates

**Course:** Science · **Title:** Physics · **Lesson:** XOR and XNOR gates — from basic gates
**Place in the curriculum:** Physics (CURRICULUM.md Unit 18), inside the electronics strand — PTB Grade 12's gate-combination lesson
**The one thing this lesson teaches:** combining the basic gates builds new logic: the XOR gate outputs 1 when its inputs differ, the XNOR when they agree — and each can be assembled from AND, OR and NOT gates, which is how control circuits are really made
**This lesson's own level:** it stands on its own — a learner can land here directly. Any earlier lesson named below is recommended first, never forced

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. Images follow the picture rule (a real photograph, or real art, with its source). GIFs come first where a thing must be shown moving or popping — a GIF here is 1–2 seconds.

## Sub lessons
1. **XOR — the difference detector** — Exclusive-OR gives output 1 when exactly one input is 1 — when the inputs differ. Its truth table (00→0, 01→1, 10→1, 11→0) makes it the circuit of comparison: adders use it for the sum bit, parity checkers use it to flag a changed bit.
2. **XNOR — the agreement detector** — Exclusive-NOR is XOR followed by NOT: output 1 when the inputs agree (00→1, 11→1) and 0 when they differ. Put side by side, the pair cover comparison both ways — difference and sameness each get a gate — and PTB teaches them as combinations, not as new primitives.
3. **Building them from basics** — XOR assembles as (A AND NOT B) OR (NOT A AND B) — an OR of the two differing cases — and XNOR as its inversion, or as (A AND B) OR (NOT A AND NOT B), the two agreeing cases. The lesson's point is architectural: any truth table can be built by OR-ing the cases that give 1, from gates already in hand.
Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- This lesson stands alone for a learner landing on it directly; anything that would help is explained inside it as it is needed.
- Recommended first, never forced: the neighbouring lessons of its strand named in the place line above.

## What the learner can do when it ends
1. Say, in their own words: exclusive-or gives output 1 when exactly one input is 1 — when the inputs differ
2. Say, in their own words: exclusive-nor is xor followed by not: output 1 when the inputs agree (00→1, 11→1) and 0 when they differ
3. Say, in their own words: xor assembles as (a and not b) or (not a and b) — an or of the two differing cases — and xnor as its inversion, or as (a and b) or (not a and not b), the two agreeing cases

## What you need
The apparatus and materials named in hands-on.md — each idea in this lesson is first met in the hand or in a worked measurement, not only on the page.

## The run of the lesson (in order)
1. **Do it first** — the learner does the opening activity before any explanation (lesson/lesson.md).
2. **The explanation** — the lesson's parts, in order (lesson/lesson.md).
   - ADD IMAGE: a picture of a drawn truth-table pair for XOR and XNOR with the 1-rows shaded, beside a gate diagram assembling XOR from two NOTs, two ANDs and an OR with the signal paths traced [Picture 36840] — the student studies the picture and names what each part shows.
   - ADD GIF: a 1–2 second GIF of the lesson's central change happening — the student watches and says what changed
   - ADD AUDIO (described slot only — no audio file is made in this build): a voice reading the lesson's key ideas aloud — the student listens, then repeats each one aloud from memory.
3. **Say it to your companion** — the learner explains the lesson's main ideas in their own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson told in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer and fill-in-the-blank — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — as described above → the student studies the picture and does what its line says.
- GIF — as described above → the student watches the change happen.
- AUDIO (described slot only) — a voice reading the key ideas aloud → the student repeats each from memory.
- VIDEO — the video-script filmed (made later) → the student watches and does the lesson's actions along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Cannot start → return to Do it first and do the opening activity with real objects or numbers before reading any explanation; the explanation is the story of that activity.
- Mixes the sub lessons up → re-read the key ideas in order; each key idea is one sub lesson compressed to a line.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
