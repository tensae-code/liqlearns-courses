# Lesson plan — The operational amplifier

**Course:** Science · **Title:** Physics · **Lesson:** The operational amplifier
**Place in the curriculum:** Physics (CURRICULUM.md Unit 18), inside the electronics strand — PTB Grade 12's integrated amplifier lesson
**The one thing this lesson teaches:** the operational amplifier is a high-gain difference amplifier on a chip: it amplifies the difference between its two inputs so enormously that, tamed by feedback, it becomes a precision building block — inverting and non-inverting amplifiers, and the comparator that switches at a threshold
**This lesson's own level:** it stands on its own — a learner can land here directly. Any earlier lesson named below is recommended first, never forced

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. Images follow the picture rule (a real photograph, or real art, with its source). GIFs come first where a thing must be shown moving or popping — a GIF here is 1–2 seconds.

## Sub lessons
1. **Two inputs, one enormous gain** — The op-amp has inverting (−) and non-inverting (+) inputs and amplifies their difference by an open-loop gain of 10⁵ or more. Alone, that gain is unusable — the output slams to a supply rail for a whisper of difference — which is exactly what the comparator exploits, and why amplifiers use feedback to trade gain for control.
2. **Virtual earth and the inverting amplifier** — Feed the output back to the − input and the amp drives that input to match the + input: with + earthed, the − input becomes a virtual earth — held at 0 V, drawing no current. An input resistor and feedback resistor then set the gain exactly: gain = −Rf/Rin, the minus sign marking the inversion. The amplifier's precision comes from two resistors, not from the chip's wild gain.
3. **Non-inverting amplifier and comparator** — Feed the signal to + instead and feedback to −, and the gain is 1 + Rf/Rin, always positive. Remove feedback altogether and the same chip is a comparator: its output snaps high or low as the inputs cross — the night switch in which an LDR divider's crossing turns on a lamp is PTB's named circuit, one chip doing both trades.
Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- This lesson stands alone for a learner landing on it directly; anything that would help is explained inside it as it is needed.
- Recommended first, never forced: the neighbouring lessons of its strand named in the place line above.

## What the learner can do when it ends
1. Say, in their own words: the op-amp has inverting (−) and non-inverting (+) inputs and amplifies their difference by an open-loop gain of 10⁵ or more
2. Say, in their own words: feed the output back to the − input and the amp drives that input to match the + input: with + earthed, the − input becomes a virtual earth — held at 0 v, drawing no current
3. Say, in their own words: feed the signal to + instead and feedback to −, and the gain is 1 + rf/rin, always positive

## What you need
The apparatus and materials named in hands-on.md — each idea in this lesson is first met in the hand or in a worked measurement, not only on the page.

## The run of the lesson (in order)
1. **Do it first** — the learner does the opening activity before any explanation (lesson/lesson.md).
2. **The explanation** — the lesson's parts, in order (lesson/lesson.md).
   - ADD IMAGE: a picture of a drawn op-amp triangle with + and − inputs, in three small circuit insets — the inverting amplifier with Rin and Rf and a virtual-earth mark, the non-inverting amplifier, and the comparator feeding a lamp through a relay [Picture 36839] — the student studies the picture and names what each part shows.
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
