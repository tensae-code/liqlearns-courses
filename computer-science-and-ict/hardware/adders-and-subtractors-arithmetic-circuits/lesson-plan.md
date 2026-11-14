# Lesson plan — Adders and Subtractors — Arithmetic Circuits

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Adders and Subtractors — Arithmetic Circuits
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Arithmetic circuits do binary arithmetic with gates: a half adder adds two bits (sum = XOR, carry = AND), a full adder adds two bits plus a carry-in (two half adders and an OR), full adders chained carry-out to carry-in make a parallel adder for whole words, and the same adder subtracts when the second number is passed through XOR gates controlled by a subtract signal that also adds the two's-complement 1 — one circuit, both operations.
**This lesson's own level:** It stands on two earlier lessons of Montenegro's climb at once: binary arithmetic (what must be computed, including two's complement) and logic gates (XOR and AND as the parts). The learner should be able to add binary by hand before seeing it wired.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Half adders and full adders** — The half adder adds two one-bit numbers A and B: Sum = A ⊕ B, Carry = A · B — one XOR and one AND gate. It is 'half' because it cannot accept a carry from a previous column. The full adder adds A, B and a carry-in Cin: built from two half adders and an OR gate — the first half adder adds A and B, the second adds that sum to Cin, and the OR of the two carries is the carry-out Cout. Chaining full adders carry-out to carry-in builds a parallel (ripple-carry) adder that adds whole words, one full adder per bit.
2. **Subtractors — and one circuit that does both** — The half subtractor and full subtractor compute A − B bit by bit with a difference and a borrow (difference = XOR again; borrow from AND of the inverted minuend). But the book's practical route is the complement method from the arithmetic lesson: feed B through XOR gates whose second input is a control line SUB — with SUB = 0 the XORs pass B unchanged and Cin = 0 (addition); with SUB = 1 the XORs invert B and Cin = 1 adds the two's-complement +1 (subtraction). One adder/subtractor unit therefore does both operations, selected by a single control bit.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Binary Arithmetic and Logic Gates — NOT, AND, OR, NAND, NOR, XOR. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Write the half adder's truth table and give Sum = A ⊕ B, Carry = A · B.
2. Explain why the half adder is only 'half', and build the full adder from two half adders and an OR gate.
3. Trace a word addition through a chain of full adders, carry-out to carry-in.
4. Explain how XOR gates steered by SUB, plus Cin = SUB, turn the same adder into a subtractor using two's complement.

## What you need
Paper and a pencil for tracing sums bit by bit. A simulator (TINA or Circuit Wizard) is the book's own way to see the carries run.

## The run of the lesson (in order)
1. **Do it first** — Your pencil added 1011 + 0110 by watching four columns. A machine must do the same work with no pencil and no watching — just gates, wired once, answering in billionths of a second. The beautiful part: the whole adder is hiding inside two truth tables you already know. XOR gives the sum of two bits; AND gives their carry. This lesson wires arithmetic out of logic. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a full adder opened up: two half-adder boxes and an OR gate joining their carries into Cout — the student points along the path of one input bit through both half adders to the Sum output.
   - ADD IMAGE: a picture of the 4-bit adder/subtractor with the B line passing through XOR gates steered by the single SUB line, SUB also feeding the first carry-in — the student says what each XOR gate does when SUB is 0 and when SUB is 1, before reading the text again.
   - ADD GIF: a GIF of a carry rippling down a chain of full adders as 1111 + 0001 is computed, each stage lighting as the carry arrives — the student predicts the final sum aloud before the last stage lights.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a full adder opened up: two half-adder boxes and an OR gate joining their carries into Cout → the student points along the path of one input bit through both half adders to the Sum output.
- IMAGE — a picture of the 4-bit adder/subtractor with the B line passing through XOR gates steered by the single SUB line, SUB also feeding the first carry-in → the student says what each XOR gate does when SUB is 0 and when SUB is 1, before reading the text again.
- GIF — a GIF of a carry rippling down a chain of full adders as 1111 + 0001 is computed, each stage lighting as the carry arrives → the student predicts the final sum aloud before the last stage lights.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Memorises Sum = XOR without seeing why → rebuild the half adder's table by adding two bits in all four ways; the Sum column *is* the XOR column, discovered, not decreed. Forgets Cin in the full adder → a column of a real addition always has three guests: A, B and the carry from the right-hand neighbour; the 'half' adder's missing door is the whole reason the full adder exists. Sets SUB = 1 but leaves Cin at 0 in subtraction → inverting B gives only ones' complement; the +1 that completes two's complement arrives through Cin, which is why Cin is wired to SUB itself.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
