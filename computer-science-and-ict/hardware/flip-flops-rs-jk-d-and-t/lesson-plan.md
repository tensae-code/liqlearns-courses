# Lesson plan — Flip-Flops — RS, JK, D and T

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Flip-Flops — RS, JK, D and T
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A flip-flop is a circuit built from gates wired in a loop that remembers one bit: it holds its output until its inputs order a change. The family — RS (set/reset), JK (RS with the forbidden combination fixed), D (copies its input when clocked) and T (toggles when clocked) — is the memory cell from which registers and counters are built.
**This lesson's own level:** It stands on the logic gates lesson before it in Montenegro's climb — the learner must already read gate symbols and truth tables, because a flip-flop is gates wired back into themselves. The clock idea is taught inside the lesson, so nothing else is needed first.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What a flip-flop is — and the RS flip-flop** — A flip-flop (bistable) has two stable states and two outputs, Q and its opposite Q̄; it keeps its state until inputs order a change — it is a one-bit memory. The RS (set–reset) flip-flop, built from two NAND (or NOR) gates cross-coupled: S = set (Q becomes 1), R = reset (Q becomes 0), both inactive = hold, and both active at once is forbidden because it drives Q and Q̄ to the same value and leaves the next state undecided.
2. **JK, D and T flip-flops** — The JK flip-flop is the RS with the forbidden case repaired: J acts like S, K like R, but J and K both active makes the flip-flop toggle — flip to the opposite state on each clock tick. The D flip-flop has one data input D: on the clock tick, Q becomes whatever D is — the standard storage cell. The T flip-flop has one input T: while T = 1 it toggles on every tick; while T = 0 it holds — so it halves the clock frequency and is the counter's building block.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Logic Gates — NOT, AND, OR, NAND, NOR, XOR, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a flip-flop is — a bistable, one-bit memory with outputs Q and Q̄ — and how it differs from a gate.
2. Run the RS flip-flop through set, hold, reset and hold, and explain why both inputs active is forbidden.
3. State what J and K do in a JK flip-flop, including the toggle that replaces the forbidden case.
4. Say what a D flip-flop does on a clock tick, and what a T flip-flop does while T = 1 and while T = 0.

## What you need
Paper and a pencil. A simulator (TINA or Circuit Wizard) makes the remembering visible; the book pairs this theory with simulation and bench work.

## The run of the lesson (in order)
1. **Do it first** — Every gate so far has been forgetful: change the input and the output forgets the past instantly. But a computer must remember — even one single bit: 'the answer was 1'. Where can a 1 be kept, in a world made of gates? This lesson answers with a trick: wire two gates in a loop, feeding each other — and the loop holds its state like a knot holds its shape. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two NAND gates cross-coupled in a loop, outputs Q and Q̄, the four input cases beside it with the forbidden case crossed out — the student traces the loop with a finger and talks the circuit through set, hold, reset, hold.
   - ADD IMAGE: a picture of the JK, D and T flip-flops as three labelled boxes with clock arrows, Q and Q̄ outputs — the student points at each box and says its verb: sets-resets-toggles, copies, toggles-or-holds.
   - ADD GIF: a GIF of a clock pulse train entering a T flip-flop and its output Q flipping on every tick, the output wave visibly half the clock's speed — the student counts the ticks and the flips aloud and says the output's rate compared with the clock.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two NAND gates cross-coupled in a loop, outputs Q and Q̄, the four input cases beside it with the forbidden case crossed out → the student traces the loop with a finger and talks the circuit through set, hold, reset, hold.
- IMAGE — a picture of the JK, D and T flip-flops as three labelled boxes with clock arrows, Q and Q̄ outputs → the student points at each box and says its verb: sets-resets-toggles, copies, toggles-or-holds.
- GIF — a GIF of a clock pulse train entering a T flip-flop and its output Q flipping on every tick, the output wave visibly half the clock's speed → the student counts the ticks and the flips aloud and says the output's rate compared with the clock.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks a flip-flop is a kind of gate → a gate forgets, a flip-flop remembers: the loop is the difference; if there is no feedback wire, there is no memory. Confuses set and reset → S makes Q = 1 (set like setting a flag up), R makes Q = 0 (reset like putting it back down). Expects D to follow its input continuously → D copies only on the clock tick; between ticks it holds, and that holding is the storage.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
