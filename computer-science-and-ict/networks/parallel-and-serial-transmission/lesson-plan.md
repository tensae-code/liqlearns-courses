# Lesson plan — Parallel and Serial Transmission

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Parallel and Serial Transmission
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Networks on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** parallel and serial transmission: sending bits many-at-once along parallel wires against one-after-another along a single line — their speeds, costs and where each survives (Bangladesh HSC ICT, Chapter 2, §2.1.4).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Parallel — many bits at once** — **Parallel transmission** sends a whole group of bits **at the same time**, each on its own wire — eight wires carry a byte in one step. It is fast per step and simple in idea, but expensive in road: many wires, and over distance the bits drift out of step (**skew**) until the group arrives ragged. Parallel therefore lives at **short distances** — inside the computer and to nearby devices — where its wires are short and its speed is real.
2. **Serial — one bit after another** — **Serial transmission** sends bits **one after another** along a single channel: slower per step, but one road serves any distance, the bits cannot fall out of step because they queue, and the cost stays low. Nearly everything that travels far is serial — network cables, internet links, the connections of this whole title. The comparison closes the lesson: parallel wins the sprint inside the machine; serial wins every journey beyond it — which is why the modern world is built serial, and why the next lesson's question — how the receiver keeps time with the sender — matters at all.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Networks on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A whole group of bits, each on its own wire
2. Eight
3. Bits drifting out of step over distance
4. Short distances — inside the computer and to nearby devices

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Eight messengers run side by side, each carrying one letter of a word. Or one messenger runs eight times. Both deliver the word — but the roads, the cost and the failures differ completely. Data transmission makes the same choice, and this lesson compares its two answers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of parallel — many bits at once as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of serial — one bit after another in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of parallel — many bits at once → the student studies the picture and names what each part shows
- GIF — a GIF of serial — one bit after another in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
