# Lesson plan — The Artificial Neuron

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** The Artificial Neuron
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** an artificial neuron is a small calculating unit: it receives numbers as inputs, multiplies each by a weight, adds them (with a bias), and passes the sum through an activation function to produce its output — learning, in a neural network, means adjusting the weights until the outputs come out right.
**This lesson's own level:** It stands on Training and Optimising an AI System just before it in Germany's strand — the 'insides' that training adjusts are this lesson's weights — and on plain multiplication and addition.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Inside one neuron — inputs, weights, sum** — Inputs x₁…xₙ arrive as numbers; each has a weight w — how much that input counts, positive (votes for) or negative (votes against). The neuron forms the weighted sum, adds a bias b (its built-in tendency), giving the net input z = w₁x₁ + w₂x₂ + … + b. A worked two-input example is computed in full.
2. **From sum to output — activation, and what learning adjusts** — The activation function turns z into the output: the step function (fire 1 if z ≥ threshold, else 0) as the book's simple form, with smoother functions named. Learning defined concretely: training adjusts the weights and the bias — nothing else — until outputs fit the examples.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the New Technologies lesson Training and Optimising an AI System in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Compute a neuron's output from given inputs, weights, bias and a simple activation rule.
2. Say what a weight means — how much an input counts — in one sentence.
3. Say what training changes inside a neuron, and what it never changes.

## What you need
Paper and a pencil, and a calculator if the class prefers — the arithmetic is small numbers, done by hand first so the machine in the head is yours.

## The run of the lesson (in order)
1. **Do it first** — A single brain cell is not clever. It receives signals, weighs them up, and decides whether to fire. Copy that humble unit in arithmetic and you get the atom of modern AI — small enough to compute fully on one line, and the next lesson will stack thousands of them into a network. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of three input lines with weight labels running into one neuron circle, the weighted sum forming inside and the bias entering from above — the student traces one input's journey and says its contribution to the sum.
   - ADD IMAGE: a picture of the step activation function — flat at 0, jumping to 1 at the threshold — with two worked values marked on it — the student places a third value on the graph and states the neuron's output.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of three input lines with weight labels running into one neuron circle, the weighted sum forming inside and the bias entering from above → the student traces one input's journey and says its contribution to the sum.
- IMAGE — a picture of the step activation function — flat at 0, jumping to 1 at the threshold — with two worked values marked on it → the student places a third value on the graph and states the neuron's output.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Adds inputs without weights → the weights are the judgement: an unweighted sum listens to everything equally, which is no judgement at all. Thinks training rewrites the activation → design fixes the activation; training tunes only weights and bias.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
