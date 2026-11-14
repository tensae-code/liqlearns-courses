# Lesson plan — Encoders and Decoders

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Encoders and Decoders
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** An encoder turns one active input line out of many into a binary code (a decimal-to-BCD encoder turns the pressed digit key into that digit's BCD code), and a decoder does the reverse — it turns a binary code into one active output line out of many (a 2-to-4 decoder lights exactly the output whose number matches the 2-bit input).
**This lesson's own level:** It stands on the codes lesson (BCD) and the logic gates lesson in Montenegro's climb: the learner already knows what a code is and what gates do, because an encoder is gates wired to produce a code and a decoder is gates wired to obey one.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Encoders — many lines in, a code out** — An encoder has 2ⁿ (or fewer) input lines and n output lines; the one input line that is active determines the binary code on the outputs. The book's example: the decimal-to-BCD encoder with ten inputs (one per digit key 0–9) and four outputs giving the BCD code of the pressed digit — output bit A (8) is the OR of inputs 8 and 9, bit B (4) the OR of 4, 5, 6, 7, and so on, so the encoder is built from OR gates. Only one input may be active at a time in the simple encoder.
2. **Decoders — a code in, one line out** — A decoder has n input lines and up to 2ⁿ output lines; the binary code on the inputs activates exactly the one output line whose number matches. The book's example: the 2-to-4 decoder — inputs A and B select output 0, 1, 2 or 3 — built from AND gates with inverters, one AND per output (each output is one minterm of the inputs). Decoders choose: one memory address, one display digit, one device — wherever a binary number must pick one thing out of many. Decoder outputs joining a display driver light the chosen digit in BCD-to-seven-segment work.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Codes — BCD and ASCII, and Logic Gates — NOT, AND, OR, NAND, NOR, XOR. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what an encoder does and give the outputs of a decimal-to-BCD encoder for any pressed digit.
2. Derive each output bit of the decimal-to-BCD encoder as an OR of the correct input lines.
3. Say what a decoder does, and work a 2-to-4 decoder for all four input codes.
4. State the 2ⁿ rule both ways: n outputs name up to 2ⁿ encoder inputs; n decoder inputs select up to 2ⁿ outputs — and name jobs each circuit does.

## What you need
Paper and a pencil. Ten fingers help for the decimal side of the encoder — one finger per digit key.

## The run of the lesson (in order)
1. **Do it first** — Press the key '7' on a lift panel. One button out of ten was pressed — how does the lift's controller receive that as bits it can use? And the other way: the controller decides 'floor 3' in binary — how does exactly one lamp, one wire out of many, get chosen? The two circuits of this lesson are the two directions of that conversation. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the decimal-to-BCD encoder box with ten input lines and four outputs, the 8-output opened to show its OR gate fed by lines 8 and 9 — the student says which input lines must feed the 4-output's OR gate before reading the answer in the lesson.
   - ADD IMAGE: a picture of the 2-to-4 decoder with input 10 lighting only output 2, its AND gate fed by A and by inverted B — the student draws which gate feeds output 1 and names its inputs, plain and inverted.
   - ADD GIF: a GIF of a finger pressing key after key on a ten-key pad while four output lamps spell each digit's BCD code — the student calls each BCD code aloud before the lamps finish lighting.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the decimal-to-BCD encoder box with ten input lines and four outputs, the 8-output opened to show its OR gate fed by lines 8 and 9 → the student says which input lines must feed the 4-output's OR gate before reading the answer in the lesson.
- IMAGE — a picture of the 2-to-4 decoder with input 10 lighting only output 2, its AND gate fed by A and by inverted B → the student draws which gate feeds output 1 and names its inputs, plain and inverted.
- GIF — a GIF of a finger pressing key after key on a ten-key pad while four output lamps spell each digit's BCD code → the student calls each BCD code aloud before the lamps finish lighting.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Swaps the pair → encoder squeezes many lines INTO a code (it encodes), decoder spreads a code OUT to one line (it decodes a number into a choice). Tries to give the decoder more outputs than 2ⁿ → the input code only has 2ⁿ different patterns, so there is nothing to name a further output with. Presses two encoder keys in a thought experiment and trusts the output → the simple encoder assumes one active input; two keys give a wrong, mixed code.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
