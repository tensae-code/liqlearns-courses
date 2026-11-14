# Lesson plan — Counters — Series, Parallel and Ring

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Counters — Series, Parallel and Ring
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A counter is a chain of flip-flops that steps through a fixed sequence of binary states, one per clock pulse, and so counts the pulses: in a series (ripple) counter each flip-flop is clocked by the previous one's output so the change ripples down the chain, in a parallel (synchronous) counter all flip-flops share the clock and change together, and in a ring counter a single 1 circulates round a closed loop of flip-flops, giving one active output per state.
**This lesson's own level:** It stands on flip-flops and registers in Montenegro's climb — the counter is the T flip-flop's toggle behaviour put in a chain, and the learner should already be able to say what a T flip-flop does per tick.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Series counters — the ripple chain** — A series (ripple, asynchronous) counter: T (or JK) flip-flops in a chain where the first is clocked by the input pulses and each next flip-flop is clocked by the previous flip-flop's output. Because each stage toggles the next at half its rate, the chain's outputs read as a binary count: a 3-bit counter steps 000, 001, 010, 011, 100, 101, 110, 111, then wraps to 000 — it counts modulo 8 (2ⁿ states for n flip-flops, then repeats). The counting change ripples stage by stage, each stage's delay adding up — simple, but the far stages settle late, which limits speed.
2. **Parallel counters and ring counters** — A parallel (synchronous) counter clocks every flip-flop from the same pulse line at the same instant; extra gates between stages decide which flip-flops toggle on each pulse (a stage toggles when all lower stages are 1), so the whole count changes together with no ripple — faster and clean, at the cost of more wiring. A ring counter closes a shift register into a loop and sets a single 1 circulating: n flip-flops give n states, exactly one output active at a time, each pulse moving the active output one place — a counter whose state can be read without decoding.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Flip-Flops — RS, JK, D and T, and Registers — Stationary and Shift, the lessons before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Build the state sequence of a series (ripple) counter and say why the counting change ripples and what that costs.
2. State that an n-bit binary counter has 2ⁿ states and counts modulo 2ⁿ.
3. Explain how a parallel (synchronous) counter clocks all stages together and what its extra gates decide.
4. Describe a ring counter — a single 1 circulating in a closed shift-register loop — and say why it needs no decoding.

## What you need
Paper and a pencil — counting sequences are written out state by state. Fingers help: count your own pulses aloud for the hands-on start.

## The run of the lesson (in order)
1. **Do it first** — Tap the desk once per second: one, two, three, four. Your taps are pulses. Could a row of flip-flops keep that count — not approximately, but exactly, in binary, forever, without you? It can, and the circuit is surprisingly small. This lesson builds it three ways and shows what each way costs and buys. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of three chained T flip-flops with the eight counting states 000–111 under successive pulses and the wrap-around arrow to 000 — the student writes the next state after 101 before reading on, and the state after 111.
   - ADD IMAGE: a picture of a parallel counter's shared clock line and watching AND gates beside a ring counter drawn as a circle with one travelling 1 — the student points at what is the same in the two pictures (flip-flops, clock) and what differs (chaining versus loop).
   - ADD GIF: a GIF of a ripple counter counting: the near stage flipping instantly, the far stages flipping one after another in a visible wave — the student says 'ripple' at the moment the wave travels, and contrasts it with all stages flipping together.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of three chained T flip-flops with the eight counting states 000–111 under successive pulses and the wrap-around arrow to 000 → the student writes the next state after 101 before reading on, and the state after 111.
- IMAGE — a picture of a parallel counter's shared clock line and watching AND gates beside a ring counter drawn as a circle with one travelling 1 → the student points at what is the same in the two pictures (flip-flops, clock) and what differs (chaining versus loop).
- GIF — a GIF of a ripple counter counting: the near stage flipping instantly, the far stages flipping one after another in a visible wave → the student says 'ripple' at the moment the wave travels, and contrasts it with all stages flipping together.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Writes the sequence in decimal order of effort, not binary → write the states as the chain does it: the first output toggles every pulse, the next every two, the next every four; read the row as a binary number. Expects a 4-flip-flop ring counter to have 16 states → the ring holds one moving 1, so its states are the 1's positions: exactly n. Thinks synchronous means 'without a clock' → it means the opposite discipline: one clock, heard by all stages at the same instant.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
