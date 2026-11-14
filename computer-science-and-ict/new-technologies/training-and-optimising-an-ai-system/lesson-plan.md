# Lesson plan — Training and Optimising an AI System

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Training and Optimising an AI System
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** an AI system is made, not found: data is gathered and split into a training part the system may learn from and a test part it has never seen; training adjusts the system until its errors on the training data shrink, and optimising means tuning the choices around that training — and the honest measure of the finished system is its score on the unseen test data, not on what it practised.
**This lesson's own level:** It stands on the machine-learning lesson beside it in this course (computers that learn from data) and on Knowledge-Based and Data-Based AI just before it in Germany's strand.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **From idea to trained system — data, split, train** — The stages: frame the task; gather and clean labelled data; split it into training data and held-back test data; choose a model shape; train — the learning procedure repeatedly measures the system's error on the training data and adjusts it down.
2. **Optimising — and the trap called overfitting** — Judgement day is the test data: accuracy there is the honest score. Overfitting: a system can memorise the training examples — perfect training score, poor test score — like a candidate who memorised last year's paper. Optimising tunes the settings around training (how much data, how complex a model, how long to train — hyperparameters) and is judged only by test performance.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the New Technologies lessons Machine Learning — Computers That Learn From Data and Knowledge-Based and Data-Based AI in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Walk an AI project through its stages — data, split, train, test — in order.
2. Say what overfitting is, and how unseen test data exposes it.
3. Name two optimising choices a builder tunes, and say what 'better' is judged by.

## What you need
Paper and a pencil. The hands-on trains a one-rule classifier on real classmates' data, split honestly — no device needed.

## The run of the lesson (in order)
1. **Do it first** — A student who practises only the exact questions on last year's paper, then faces a fresh paper, discovers the difference between memorising and learning. AI systems face the same examination — and this lesson is about how their builders set it fairly, and improve the candidate between sittings. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a circular training loop — examples in, answers compared, error measured, insides adjusted — around a small model — the student walks the loop once aloud, saying what changes on each pass.
   - ADD IMAGE: a picture of two lines over training time — training error falling steadily, test error falling then rising — with the sweet spot marked — the student points to where training should have stopped and says what the rising line means.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a circular training loop — examples in, answers compared, error measured, insides adjusted — around a small model → the student walks the loop once aloud, saying what changes on each pass.
- IMAGE — a picture of two lines over training time — training error falling steadily, test error falling then rising — with the sweet spot marked → the student points to where training should have stopped and says what the rising line means.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Judges the system on its training score → the training score measures memory of practice; the test score measures learning. Asks to tune until the test score is perfect → test data spent on tuning is no longer unseen; honesty needs a measurement the tuning never touched.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
