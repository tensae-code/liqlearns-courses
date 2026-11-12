# Lesson plan — Analogue and digital signals — sampling rate and sampling precision

**Course:** Science · **Title:** Physics · **Lesson:** Analogue and digital signals — sampling rate and sampling precision
**Place in the curriculum:** Physics (CURRICULUM.md Unit 18) — a new lesson built for the North Macedonia placement named in lesson/sources.md
**The one thing this lesson teaches:** an analogue signal becomes numbers by sampling — reading its value at regular instants, at a sampling rate that must be at least twice the fastest change to be kept — and by quantisation, rounding each sample to one of 2^n levels set by the sampling precision in bits; AD and DA converters are the two directions of the doorway, and sampling and quantisation errors are the price of crossing it
**This lesson's own level:** it stands on its own — a learner can land here directly. Earlier lessons make a good preparation and are recommended, never forced

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. Images follow the picture rule (a real photograph, or real art, with its source). GIFs come first where a thing must be shown moving or popping — a GIF here is 1–2 seconds.

## Sub lessons
1. **Sampling — reading a smooth signal at instants** — An analogue signal changes continuously — every instant, every value. To store it as numbers, an analogue-to-digital converter samples it: it reads the value at regular instants, the sampling rate counting the reads per second (in hertz). Between samples the signal is not recorded, so sampling always loses something: sample too slowly and fast changes slip between the reads — the sampling error grows, and a too-slow rate can even invent false low frequencies (aliasing). The working rule: sample at least twice as fast as the fastest change you must keep — which is why CD audio samples 44,100 times a second. North Macedonia's Grade 13 book (Theme 6 §6.1) builds analogue–digital conversion on exactly this: sampling rate, sampling precision, sampling error, converters, embedded systems.
2. **Quantisation and converters — how fine the numbers are** — Each sample must also be rounded to a level the system can store: that rounding is quantisation, and the sampling precision — the number of bits per sample — sets how many levels exist: 8 bits give 256 levels, 16 bits give 65,536, and the finer the levels, the smaller the quantisation error. The AD converter does sampling and quantising on the way in; the DA converter rebuilds a smooth signal from the numbers on the way out. Around them sit embedded systems — small dedicated computers inside devices — that sample the world, decide, and act: the conversion pair is the doorway between the analogue world and every digital machine.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the lessons nearest this one in the title — recommended, never forced.

## What the learner can do when it ends
1. Explain and use the lesson's central idea in the learner's own words.
2. Work the lesson's standard tasks, as set in the Do It Yourself block.
3. State the key ideas in the learner's own words, in order.
4. Answer the lesson's questions from the lesson text alone.

## What you need
For the hands-on: the items named in hands-on.md — ordinary household items only.

## The run of the lesson (in order)
1. **Do it first** — the learner does the opening activity before any explanation (lesson/lesson.md).
2. **The explanation** — the lesson's parts, in order (lesson/lesson.md).
   - ADD IMAGE: a picture of a smooth analogue wave with dots marking the sampling instants along it, the staircase of stored digital values drawn over the same axes, and horizontal lines marking the quantisation levels — the student points to one sampling interval and one quantisation step and says what each one costs [Picture 36712] — the student studies the picture and does what its line says
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
- Cannot start → return to Do it first and do the opening activity with real objects before reading any explanation; the explanation is the story of that activity.
- Mixes the sub lessons up → re-read the key ideas in order; each key idea is one sub lesson compressed to a line.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
