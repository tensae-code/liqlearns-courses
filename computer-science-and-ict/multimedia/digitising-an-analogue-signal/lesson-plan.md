# Lesson plan — Digitising an Analogue Signal

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Digitising an Analogue Signal
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** An analogue signal varies smoothly and takes any value; to store it in a computer it must be digitised in three steps — sampling (measuring the signal at regular instants, the sampling rate), quantisation (rounding each measurement to the nearest of a fixed set of levels, fixed by the bit depth) and coding (writing each level's number in binary) — and the rate and depth chosen decide how faithfully the digital copy follows the original.
**This lesson's own level:** It stands on the codes lessons of Montenegro's climb — a digitised value is just a binary code for a level — and on nothing else; the analogue/digital contrast is built inside the lesson from sound and voltage examples.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Sampling — measuring at regular instants** — Sampling: the signal's value is measured at evenly spaced instants and only those measurements are kept; the number of measurements per second is the sampling rate (frequency), measured in hertz. Between samples the signal is not recorded at all, so the rate must be high enough to follow the signal's fastest changes — the sampling theorem (Nyquist) says the rate must be at least twice the highest frequency in the signal; CD audio uses 44.1 kHz because hearing reaches about 20 kHz. Too low a rate loses detail and produces aliasing — false, lower patterns that were never in the original.
2. **Quantisation and coding — levels, bits and the size of the copy** — Quantisation: each sample's measured value is rounded to the nearest of a fixed number of levels; the number of levels is set by the bit depth — n bits give 2ⁿ levels (8 bits: 256 levels; 16 bits: 65 536). The rounding loses a little of every sample — quantisation error, heard as noise — and more bits make the steps smaller and the error quieter. Coding: each level's number is written in binary, and the digitised signal is the resulting stream of codes. Together: file size = sampling rate × bit depth × seconds (per channel).

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Codes — BCD and ASCII, where a value first became a pattern of bits. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what sampling is and what the sampling rate measures, in hertz.
2. State the sampling theorem — sample at least twice the highest frequency — and name the error (aliasing) that breaks it.
3. Say what quantisation is, how bit depth sets the number of levels as 2ⁿ, and what quantisation error is.
4. Describe coding as the final step and compute a digitised recording's size from rate × depth × seconds.

## What you need
Paper, a pencil and a ruler — the learner draws a smooth wave and samples it by hand. A phone's voice recorder, if available, gives a living example for the hands-on.

## The run of the lesson (in order)
1. **Do it first** — Your voice, travelling as sound, is smooth: it swells and fades through every in-between value, never jumping. A computer holds only separated numbers — 0s and 1s, counted levels. How can something smooth become something counted without losing what makes it your voice? Three steps do it, and this lesson works each one by hand. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one smooth wave sampled three ways — densely, at the Nyquist limit, and too sparsely with a false slow wave sketched through the sparse samples — the student points at the sparse version and explains in words where the false wave came from.
   - ADD IMAGE: a picture of a staircase of quantisation levels over a smooth curve, each sample snapped to its nearest rung and the small error gaps marked — the student says what happens to the error and to the file when the staircase is given twice as many rungs.
   - ADD GIF: a GIF of a moving wave being sampled: dots appearing on the curve at regular ticks, each dot dropping to its nearest level line and turning into a binary code — the student counts the samples appearing in one second of the GIF's clock and names the three steps as they happen.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one smooth wave sampled three ways — densely, at the Nyquist limit, and too sparsely with a false slow wave sketched through the sparse samples → the student points at the sparse version and explains in words where the false wave came from.
- IMAGE — a picture of a staircase of quantisation levels over a smooth curve, each sample snapped to its nearest rung and the small error gaps marked → the student says what happens to the error and to the file when the staircase is given twice as many rungs.
- GIF — a GIF of a moving wave being sampled: dots appearing on the curve at regular ticks, each dot dropping to its nearest level line and turning into a binary code → the student counts the samples appearing in one second of the GIF's clock and names the three steps as they happen.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks sampling stores the whole wave between samples → nothing between samples is kept at all; the copy is only the measurements, and faithfulness comes from sampling often enough that little can hide between them. Mixes rate and depth → rate is *how often* (time), depth is *how fine* (levels); a recording can be dense in one and coarse in the other. Believes quantisation error can be removed later → the rounding loss happens at digitising and is permanent; more bits at the start is the only cure.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
