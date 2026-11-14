# Lesson plan — Multiplexers and Demultiplexers

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Multiplexers and Demultiplexers
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A multiplexer is a data selector: many inputs, one output, and select lines whose binary code chooses which input is connected to the output at any moment (a 4-to-1 multiplexer has 4 data inputs, 1 output and 2 select lines). A demultiplexer does the reverse — one input, many outputs, the select code choosing which output receives the data — so the pair can share one line between many senders and many receivers.
**This lesson's own level:** It stands on the encoders-and-decoders lesson before it in Montenegro's climb — the select lines are read exactly like a decoder's code, and the learner who has met AND and OR gates can follow the multiplexer's insides at once.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The multiplexer — many inputs, one chosen** — A multiplexer (MUX) has 2ⁿ data inputs, n select (address) lines and one output; the binary code on the select lines connects exactly that numbered input to the output. The 4-to-1 MUX: inputs D0–D3, select lines S1 S0, output Y = D0 when the select is 00, D1 when 01, D2 when 10, D3 when 11. Built from AND gates (one per input, enabled by the select pattern) feeding one OR gate. A MUX is a digitally controlled switch, and it can also be wired as a function generator: fix its data inputs to 0s and 1s and it outputs a chosen switching function of its select lines.
2. **The demultiplexer — one input, delivered to the chosen output** — A demultiplexer (DEMUX) has one data input, n select lines and 2ⁿ outputs; the select code routes the input to exactly that numbered output, all other outputs stay 0. A 1-to-4 DEMUX is the 4-to-1 MUX run in reverse, and it is the same hardware shape as a decoder whose code input is used as an enable. Together, MUX and DEMUX let many senders share one transmission line: the MUX picks whose data travels, the DEMUX at the far end delivers it to the matching receiver, and both select lines are kept in step.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Encoders and Decoders, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a multiplexer does and work a 4-to-1 MUX for any select code.
2. State the select-line rule: 2ⁿ data inputs need n select lines.
3. Explain the multiplexer's insides — one AND gate per input opened by its select pattern, all feeding one OR gate.
4. Say what a demultiplexer does, how it relates to a decoder with an enable, and how a MUX–DEMUX pair shares one line between many senders and receivers.

## What you need
Paper and a pencil. A row of four different-coloured pens makes a good stand-in for four data sources in the hands-on work.

## The run of the lesson (in order)
1. **Do it first** — Four security cameras, one screen, one cable running across the building. All four cannot use the cable at the same instant — but they can take turns so fast the guard never notices. Something must choose, moment by moment, which camera owns the cable. At the far end, something must send the arriving signal to the right place. This lesson is those two choosers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the 4-to-1 multiplexer twice — as a rotary switch turned by its select lines and as a block diagram with D0–D3, Y and S1 S0 — the student sets the switch for select code 10 in their head and says which input reaches Y.
   - ADD IMAGE: a picture of a MUX and DEMUX facing each other across one line, four senders on the left and four receivers on the right, both select dials showing the same code — the student traces the path of sender 3's data across the picture and says what both select codes must be.
   - ADD GIF: a GIF of the select code counting 00, 01, 10, 11 while the output of a MUX jumps from input to input, each input a different coloured wave — the student calls out which input owns the output at each step of the count.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the 4-to-1 multiplexer twice — as a rotary switch turned by its select lines and as a block diagram with D0–D3, Y and S1 S0 → the student sets the switch for select code 10 in their head and says which input reaches Y.
- IMAGE — a picture of a MUX and DEMUX facing each other across one line, four senders on the left and four receivers on the right, both select dials showing the same code → the student traces the path of sender 3's data across the picture and says what both select codes must be.
- GIF — a GIF of the select code counting 00, 01, 10, 11 while the output of a MUX jumps from input to input, each input a different coloured wave → the student calls out which input owns the output at each step of the count.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Confuses select lines with data inputs → data lines carry the signal; select lines only choose — they are the address, not the message. Gives an 8-to-1 MUX two select lines → the code must name 8 inputs, and 2 lines name only 4; count: 2ⁿ inputs, n lines. Thinks unselected DEMUX outputs copy the input quietly → they are 0; only the chosen output receives the data.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
