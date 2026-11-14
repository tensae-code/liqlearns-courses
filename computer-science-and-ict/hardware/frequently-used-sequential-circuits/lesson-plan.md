# Lesson plan — Frequently Used Sequential Circuits

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Frequently Used Sequential Circuits
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The sequential circuits in constant use: registers that hold words, shift registers that move them, and counters that count pulses in binary — the remembering circuits the machine's timing is built from (Moldova Grade 11, Informatică, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Registers — a word held in flip-flops** — A **register** is a **row of flip-flops holding one word** — 8, 16, 32 or 64 bits kept together, loaded together, read together: the processor's hands, holding the numbers it is working on *now*. A **shift register** adds motion: at each clock pulse its bits **move one place** along the row — the circuit form of the binary multiplication-by-2 the arithmetic lessons met, and the bridge that turns parallel words into serial streams (one bit at a time) for transmission, and back.
2. **Counters — flip-flops that count** — A **counter** is a sequential circuit whose state, advanced by each incoming **pulse**, **counts in binary**: 000, 001, 010, 011… each flip-flop a place, the clock's ticks its input. Counters **divide frequency** (each stage's output pulses at half the rate of the one before), time events, and sequence operations — the machine's patience made of gates. With them the chapter closes its ladder: gates → functions → adders and routers → memory → registers and counters → (next chapter) the whole computer's architecture.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A row of flip-flops holding one word — loaded and read together
2. 8, 16, 32 or 64 bits
3. It moves its bits one place along the row
4. Multiplication by 2 (left) — the shift of the arithmetic lessons

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The circuits chapter ends with the family that remembers at work: not the lone flip-flop of §5.5, but its organised companies — the registers and counters standing inside every processor. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of registers — a word held in flip-flops as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of counters — flip-flops that count in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of registers — a word held in flip-flops → the student studies the picture and names what each part shows
- GIF — a GIF of counters — flip-flops that count in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
