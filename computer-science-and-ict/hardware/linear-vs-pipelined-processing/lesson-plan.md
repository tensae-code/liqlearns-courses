# Lesson plan — Linear vs Pipelined Processing

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Linear vs Pipelined Processing
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The difference between linear processing — one instruction finished completely before the next begins — and pipelining, where the stages of several instructions overlap like an assembly line (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Linear processing — one at a time, whole** — In **linear (sequential) processing**, an instruction passes through **all** the machine's stages — fetch, decode, execute — and is **completely finished** before the next instruction is fetched. The picture is a single-file queue: at every moment, only **one stage is working** on the one instruction, and the other stages wait idle. Linear processing is simple to build and easy to reason about — and it wastes the machine: three stages, two always waiting.
2. **Pipelining — stages overlapping** — **Pipelining** overlaps the stages: while instruction 1 is being **executed**, instruction 2 is being **decoded** and instruction 3 is being **fetched** — like an assembly line, every stage working at once, each on a different instruction. After the line fills, one instruction **finishes on every cycle**, though each still takes its full path through the stages: pipelining raises **throughput** (instructions per time), not the speed of any single instruction. Malaysia's comparison keeps the honest cost: the line stumbles when an instruction needs a result the line has not finished yet — the neat overlap has a traffic problem at its heart, which real processors spend much of their cleverness managing.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Only after the current one is completely finished
2. Fetch, decode, execute
3. One — the others wait idle
4. Each stage works on a different instruction — execute, decode and fetch overlap

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A processor that finishes each instruction entirely before touching the next is leaving most of itself idle most of the time. Malaysia's architecture chapter sets that waste against its cure. In this lesson you compare linear processing with pipelining — stage by overlapping stage. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of linear processing — one at a time, whole as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of pipelining — stages overlapping in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of linear processing — one at a time, whole → the student studies the picture and names what each part shows
- GIF — a GIF of pipelining — stages overlapping in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
