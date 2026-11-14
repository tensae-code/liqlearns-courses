# Lesson plan — Frequently Used Combinational Circuits

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Frequently Used Combinational Circuits
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The combinational circuits in constant use: encoders and decoders that translate between codes, multiplexers and demultiplexers that route signals, and comparators — each an answer-only circuit, no memory (Moldova Grade 11, Informatică, §5.4).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Encoders and decoders — translators between codes** — An **encoder** turns **one active input line** (of 2ⁿ) into its **n-bit binary code** — the keyboard's innards, naming the pressed key. A **decoder** does the reverse: an n-bit code **activates exactly one** of 2ⁿ output lines — the circuit that chooses which memory bank, display digit or device a code addresses. The pair are mirror images around a code: the encoder compresses lines into bits; the decoder expands bits back into one chosen line.
2. **Multiplexers, demultiplexers and comparators — routers and judges** — A **multiplexer (MUX)** chooses **one of several inputs** to send to its single output — a selector switch for signals, steered by control bits; a **demultiplexer** routes one input to **one of several outputs**. A **comparator** judges two binary numbers and reports **greater, equal or less** in three outputs. Route, choose, judge: with gates, adders and these, the combinational toolkit is the whole of the machine's **present-tense** electronics — everything memoryless the CPU does is built from them.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It turns one active input line (of 2ⁿ) into its n-bit binary code
2. It activates exactly one of 2ⁿ output lines, chosen by its n-bit code
3. Inside a keyboard — naming the pressed key as a code
4. Choosing which memory bank or display digit a code addresses

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 11's circuits chapter moves from the adder to the rest of the working family: the combinational circuits — no memory, output a pure function of today's inputs — that real machines are assembled from. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of encoders and decoders — translators between codes as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of multiplexers, demultiplexers and comparators — routers and judges in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of encoders and decoders — translators between codes → the student studies the picture and names what each part shows
- GIF — a GIF of multiplexers, demultiplexers and comparators — routers and judges in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
