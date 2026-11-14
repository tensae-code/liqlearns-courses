# Lesson plan — Logic Gates — NOT, AND, OR, NAND, NOR, XOR

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Logic Gates — NOT, AND, OR, NAND, NOR, XOR
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A logic gate is the physical circuit that performs one Boolean operation: the inverter (NOT), AND and OR gates perform the three basic operations, NAND and NOR are those operations followed by an inverter and are each able to build every other gate alone, XOR and XNOR answer 'different' and 'same', and complex gates combine several operations in one package.
**This lesson's own level:** It stands on the Boolean algebra lessons before it in Montenegro's climb — each gate is one operation the learner already knows by truth table. The new thing here is only the physical side: symbols, pins and the book's own order from basic gates to complex ones.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The basic gates — inverter, AND, OR** — The inverter (NOT gate): one input, output always the opposite, drawn as a triangle with a small circle at the tip. The AND gate: output 1 only when all inputs are 1. The OR gate: output 1 when at least one input is 1. Each gate's symbol, its Boolean expression and its truth table are one and the same fact in three writings.
2. **NAND, NOR, XOR, XNOR — and complex gates** — NAND = AND followed by NOT (bubble on an AND symbol): output 0 only when all inputs are 1. NOR = OR followed by NOT: output 1 only when all inputs are 0. XOR: output 1 when inputs differ; XNOR: output 1 when inputs are the same (XOR with a bubble). NAND alone, and NOR alone, can each build NOT, AND and OR — they are universal gates, which is why real chips are built mostly from them. Complex gates (such as AND-OR-INVERT) pack a whole expression — ANDs feeding an OR feeding an inverter — into one component.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Boolean Algebra and Logic Operations — and the minimising lesson, which showed why gate counts matter. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Draw the symbols and write the expressions of the inverter, AND and OR gates, and give any gate's output for given inputs.
2. State the truth behaviour of NAND, NOR, XOR and XNOR in one sentence each.
3. Show how NAND alone builds NOT, AND and OR (and say the same is true of NOR), using De Morgan.
4. Read a complex gate such as AND-OR-INVERT and write its Boolean expression.

## What you need
Paper and a pencil for drawing gates and tables. If the school has TINA or Circuit Wizard, the hands-on part uses it — the book teaches gates together with simulation.

## The run of the lesson (in order)
1. **Do it first** — You already know NOT, AND, OR and XOR as tables on paper. Now imagine each table shrunk into a small black component with pins: signals go in on one side, the answer comes out on the other, thousands of times a second. Those components are gates, and every chip in every computer is nothing but gates connected together. This lesson names them, draws them, and shows the two gates that can build all the others. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the inverter, AND and OR gates in a row, each with symbol, expression and truth table, the inverter's bubble circled — the student sketches each gate from memory and writes its expression under the sketch.
   - ADD IMAGE: a picture of NAND, NOR, XOR and XNOR with symbols and tables, all negation bubbles picked out in colour — the student points at each bubble and says which operation it negates.
   - ADD GIF: a GIF of a NAND gate becoming an inverter as its two inputs join into one wire, then an AND as an inverter follows it, then an OR as inverters arrive on its inputs — the student predicts each new gate's table before the GIF finishes the wiring.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the inverter, AND and OR gates in a row, each with symbol, expression and truth table, the inverter's bubble circled → the student sketches each gate from memory and writes its expression under the sketch.
- IMAGE — a picture of NAND, NOR, XOR and XNOR with symbols and tables, all negation bubbles picked out in colour → the student points at each bubble and says which operation it negates.
- GIF — a GIF of a NAND gate becoming an inverter as its two inputs join into one wire, then an AND as an inverter follows it, then an OR as inverters arrive on its inputs → the student predicts each new gate's table before the GIF finishes the wiring.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Reads NAND as a new thing to memorise → it is only AND with a bubble: write the AND table and flip every output. Mixes XOR and XNOR → XOR answers 'different?', XNOR — the one with the bubble — answers 'same?'. Cannot see why NAND builds OR → that is De Morgan wearing wires: NOT(A·B) with negated inputs is exactly A + B; go back to the theorems lesson picture, break the bar.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
