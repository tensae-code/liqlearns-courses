# Lesson plan — DA and AD Converters

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** DA and AD Converters
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Converters are the border posts between the analogue world and the digital machine: a DA converter (DAC) turns a binary number into a proportional analogue voltage — most simply by a resistor ladder where each bit switches its weighted contribution — and an AD converter (ADC) turns an analogue voltage into its binary number, performing the sampling, quantisation and coding of the digitising lesson, with resolution set by its bit count and speed by its conversion time.
**This lesson's own level:** It stands on the digitising lesson just before it in Montenegro's climb — the ADC is that lesson's three steps built as a circuit — and on binary place values from the climb's first lesson. It closes the book's placed content: signals can now go both ways across the border.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **DA converters — numbers into voltage** — A DAC takes a binary word and outputs an analogue voltage proportional to the word's value: output = reference voltage × (binary value / 2ⁿ) for an n-bit converter — so the output climbs in equal steps as the input counts up, a staircase approaching a smooth ramp. A common construction is the R-2R resistor ladder: each bit, through its switch, contributes a current weighted by its place value (each lower bit half the one above), and the contributions are summed — the place values of the first lesson built from resistors. More bits = finer steps = a smoother, truer analogue output.
2. **AD converters — voltage into numbers** — An ADC does the digitising lesson in hardware: it samples the input voltage, quantises it to one of 2ⁿ levels (n = its resolution in bits) and codes the level in binary. A direct (flash-style) view: comparators compare the input against a ladder of reference levels at once and logic picks the highest level the input passes. In practice the trade is resolution against conversion time and cost: higher bits give finer levels; faster conversion follows quicker-changing signals; the choice follows the signal — slow, fine measurement wants bits; fast signals want speed.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Digitising an Analogue Signal, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Compute a DAC's output voltage from Vref × (input value / 2ⁿ), and describe the staircase its output climbs as the input counts.
2. Explain how an R–2R ladder gives each bit its binary weight of contribution.
3. State that an n-bit ADC quantises into 2ⁿ levels, and work a voltage into its output code for a stated range and bit count.
4. Name the ADC trade — resolution (bits) against conversion speed and cost — and match converter choices to a slow signal and a fast signal.

## What you need
Paper and a pencil. If the school has TINA or Circuit Wizard, the DAC's staircase output can be watched in simulation — the book's own pairing of theory and simulation.

## The run of the lesson (in order)
1. **Do it first** — Your phone does both tricks in this lesson every time you press play: a stream of numbers becomes a smooth voltage that moves a speaker — and when you record, a smooth voltage from the microphone becomes a stream of numbers. Two circuits face opposite ways across the same border. This lesson opens both. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of an R–2R ladder DAC with four bit switches, their contributions labelled ½, ¼, ⅛ and 1⁄16 of full scale — the student says which switches are on for the code 1010 and adds their contributions before reading the answer.
   - ADD IMAGE: a picture of a flash ADC: resistor ladder, column of comparators and encoder logic producing the output code — the student points at the comparator whose boundary a given input voltage just passes, and reads the code it produces.
   - ADD GIF: a GIF of a DAC's input counting upward in binary while its output voltage climbs a staircase step by step, the steps shrinking as more bits fade into view — the student calls the output for code 1000 in an 8-bit, 5 V converter before the step is drawn.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of an R–2R ladder DAC with four bit switches, their contributions labelled ½, ¼, ⅛ and 1⁄16 of full scale → the student says which switches are on for the code 1010 and adds their contributions before reading the answer.
- IMAGE — a picture of a flash ADC: resistor ladder, column of comparators and encoder logic producing the output code → the student points at the comparator whose boundary a given input voltage just passes, and reads the code it produces.
- GIF — a GIF of a DAC's input counting upward in binary while its output voltage climbs a staircase step by step, the steps shrinking as more bits fade into view → the student calls the output for code 1000 in an 8-bit, 5 V converter before the step is drawn.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Expects the DAC output to be perfectly smooth → it is a staircase, always; more bits only make the steps smaller — smoothness is approached, never reached, exactly the quantisation ladder seen from the other side. Computes levels as 2 × n → the ADC's levels are 2ⁿ: 8 bits are 256 levels, not 16. Chooses converters by price alone → the signal decides: its fastest change sets the speed, its smallest meaningful difference sets the bits; a converter is matched to a signal, not to a budget first.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
