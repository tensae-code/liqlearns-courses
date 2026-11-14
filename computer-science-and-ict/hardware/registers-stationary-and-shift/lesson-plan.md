# Lesson plan — Registers — Stationary and Shift

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Registers — Stationary and Shift
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A register is a row of flip-flops that stores a whole binary word at once: in a stationary (parallel) register every bit is written and read at the same moment, while in a shift register the bits move one place along the row on each clock tick, so data can enter and leave one bit at a time in series, or all together in parallel — the four combinations SISO, SIPO, PISO and PIPO.
**This lesson's own level:** It stands directly on the flip-flops lesson before it in Montenegro's climb — a register is that lesson's D flip-flops standing in a row under one clock. Nothing else is needed; the word 'stationary' is the book's own name for the parallel register.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Stationary registers — the whole word at once** — A stationary (parallel) register: one D flip-flop per bit, all sharing one clock. On the tick, every flip-flop copies its own data input at the same instant, so the whole word is stored in a single tick (parallel-in), and it can be read at any time from all the Q outputs together (parallel-out). The register's capacity is its number of flip-flops: an 8-bit register holds one byte. Registers are the machine's working memory cells — the CPU's own registers hold the words being computed on.
2. **Shift registers — the bits move along** — A shift register wires each flip-flop's output into the next flip-flop's input, so on every clock tick each bit moves one place along the row (left or right). Data can enter one bit at a time (serial-in) and leave one bit at a time (serial-out), or in parallel — giving SISO, SIPO, PISO and PIPO forms. Serial-in/parallel-out gathers a word arriving on one wire; parallel-in/serial-out sends a stored word down one wire. Shift registers also delay data and convert between serial and parallel forms.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Flip-Flops — RS, JK, D and T, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a register is and how many flip-flops a register of n bits contains.
2. Explain how a stationary register stores a whole word in one clock tick (parallel-in) and shows it all at once (parallel-out).
3. Trace bits through a shift register tick by tick and say where each bit goes on a tick.
4. Name SISO, SIPO, PISO and PIPO, and say which form gathers a serial stream into a word and which sends a word out serially.

## What you need
Paper and a pencil. A row of coins or bottle caps that can slide along a desk makes the shifting visible in the hands-on work.

## The run of the lesson (in order)
1. **Do it first** — One flip-flop remembers one bit. But a computer's words are eight, sixteen, sixty-four bits long — where does a whole word live while the machine works on it? And the opposite puzzle: a wire carries bits one after another, one per tick — how are they gathered into a word? Both puzzles are solved by one structure, flip-flops in a row: the register. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of eight D flip-flops in a row sharing one clock, the word 10110100 entering all at once and standing on the outputs — the student says which flip-flop holds the leftmost bit of the word, and what changes on the next tick.
   - ADD IMAGE: a picture of a four-bit shift register at four successive ticks, bits shuffling one place along at each tick — the student traces the first-entered bit's seat at every tick with a finger.
   - ADD GIF: a GIF of bits entering a shift register one per tick from a single wire, shuffling along, until the full word stands in the row and is read out in parallel — the student counts the ticks aloud and calls 'word complete' at the right tick.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of eight D flip-flops in a row sharing one clock, the word 10110100 entering all at once and standing on the outputs → the student says which flip-flop holds the leftmost bit of the word, and what changes on the next tick.
- IMAGE — a picture of a four-bit shift register at four successive ticks, bits shuffling one place along at each tick → the student traces the first-entered bit's seat at every tick with a finger.
- GIF — a GIF of bits entering a shift register one per tick from a single wire, shuffling along, until the full word stands in the row and is read out in parallel → the student counts the ticks aloud and calls 'word complete' at the right tick.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks a register is a new kind of component to memorise → it is only D flip-flops in a row under one clock; if you know the flip-flop, you know every cell of the register. Loses bits while tracing a shift → draw the row as boxes and rewrite the whole row after each tick; never try to update it in your head. Mixes SIPO and PISO → name them in the order the data travels: in first, out second — Serial-In gathers, Parallel-In then Serial-Out sends.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
