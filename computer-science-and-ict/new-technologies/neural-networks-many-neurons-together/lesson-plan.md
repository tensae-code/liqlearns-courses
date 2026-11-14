# Lesson plan — Neural Networks — Many Neurons Together

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Neural Networks — Many Neurons Together
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** a neural network wires artificial neurons in layers — an input layer taking the numbers in, hidden layers whose neurons judge small features, and an output layer giving the answer — and, trained on many examples, the layers together learn a division of labour no one programmed: early layers find simple features, later layers combine them into things like letters, faces and words.
**This lesson's own level:** It stands directly on The Artificial Neuron before it in Germany's strand, and on Training and Optimising an AI System before that — this lesson is where those two meet at full size.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Layers — how a network is wired** — Input layer: one neuron (or entry point) per input number — for an image, one per pixel value. Hidden layers between: every neuron receives the previous layer's outputs as its inputs. Output layer: one neuron per possible answer; the most-fired output is the system's answer. A forward pass traced on a tiny digit-recogniser.
2. **What the layers learn — features upon features, and image recognition** — The division of labour training discovers: first hidden layers respond to simple features (edges, strokes), later ones to combinations (loops, corners, then whole digits/faces). Image recognition as the book's worked case; training adjusts every weight in every layer against the error; depth buys power at the price of data and computation.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the New Technologies lessons The Artificial Neuron and Training and Optimising an AI System in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Draw a small network's layers and trace one input's journey to an output.
2. Say, with the image-recognition example, what hidden layers contribute that one neuron cannot.
3. Say what training adjusts across a whole network, and why depth helps and costs.

## What you need
Paper and a pencil. A class photo or a hand-drawn digit is the running example — keep it in sight while tracing the layers.

## The run of the lesson (in order)
1. **Do it first** — One neuron can judge one small thing. Yet systems built from nothing but such units read handwriting, understand speech and describe photographs. This lesson wires the units together — layers upon layers — and follows one photograph's numbers through the whole machine until an answer comes out. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a three-layer network drawn fully connected, with one photograph's journey highlighted from pixels to the winning output neuron — the student follows the highlight aloud and names what each layer hands to the next.
   - ADD IMAGE: a picture of three panels — pixels, then edge detectors lighting up, then part detectors, then whole digits — for one handwritten 9 — the student says which panel could not exist without the one before it, and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a three-layer network drawn fully connected, with one photograph's journey highlighted from pixels to the winning output neuron → the student follows the highlight aloud and names what each layer hands to the next.
- IMAGE — a picture of three panels — pixels, then edge detectors lighting up, then part detectors, then whole digits — for one handwritten 9 → the student says which panel could not exist without the one before it, and why.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks each hidden neuron was assigned its feature by a programmer → the division of labour is discovered by training; the programmer chose the shape, the data chose the jobs. Reads the output as the network 'seeing a photo' → the network sees numbers (pixel values) and answers numbers; the picture exists only at the two ends.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
