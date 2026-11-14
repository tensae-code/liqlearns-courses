# Lesson plan — The Format of a Machine Instruction

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** The Format of a Machine Instruction
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How a machine instruction is laid out in its bits: an operation code field naming what to do, and address fields naming where the data lives — the instruction format that fixes a processor's whole language (Moldova Grade 11, Informatică, §6.2).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Fields — operation code and addresses** — A **machine instruction** is a row of bits divided into **fields**. The **operation code (opcode)** field names **what to do** — add, load, store, jump — from the processor's fixed instruction set. The **address field(s)** name **where the operands are** — which registers, or which memory addresses, hold the data the operation works on. An instruction of 16 bits might spend 4 on the opcode (16 possible operations) and 12 on an address (4096 addressable cells): the format is a budget of bits, spent between variety of operations and reach of addresses.
2. **Formats by address count — three, two, one, zero** — Instructions are classed by their **address count**: a **three-address** instruction names both operands and the result's place (add a, b, c); **two-address** overwrites one operand with the result; **one-address** works with an implied **accumulator**; **zero-address** works on a **stack**, its operands understood. Fewer addresses make **shorter instructions and a simpler processor**, at the price of more instructions per job. The format chosen is the architecture's founding compromise, visible in every program the machine will ever run.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An operation code field and address field(s)
2. What to do — add, load, store, jump — from the processor's instruction set
3. Where the operands are — registers or memory addresses
4. 16 operations; a 12-bit address reaches 4096 cells

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 11's architecture chapter reaches the machine's own sentences. An instruction is not words but a pattern of bits in fields — and the pattern's layout, the format, is designed before the processor is. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of fields — operation code and addresses as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of formats by address count — three, two, one, zero in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of fields — operation code and addresses → the student studies the picture and names what each part shows
- GIF — a GIF of formats by address count — three, two, one, zero in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
