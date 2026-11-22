# Lesson plan — Controlling a Robot Arm with an HMI

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Controlling a Robot Arm with an HMI
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Programming on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A robot arm is moved by servomotors — one per joint — driven by a microcontroller board (Arduino); the human drives the machine through an HMI (human–machine interface): in the book’s build, a Python window (Tkinter) whose controls send commands over the serial link to the board, which turns them into joint movements.
**This lesson's own level:** It stands on the embedded-systems lessons (sensors, actuators, microcontrollers) and on Python basics. The build is described so the lesson stands even where the physical arm is not available.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The arm, its servomotors and the Arduino** — A servomotor turns to a commanded angle and holds it — the muscle of each joint (base, shoulder, elbow, wrist, gripper). The Arduino board is the embedded brain: it receives target angles and drives each servo in order, so a grip is a choreography of angles, not one movement.
2. **The Python interface that drives it** — The HMI: a Tkinter window with sliders and buttons for each joint; moving a control sends the command over the serial (USB) link to the Arduino; the human sees, judges and corrects through the interface — the loop of the embedded-systems lessons, with the human outside the arm but inside the control.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the New Technologies lessons on embedded computing and on microcontrollers, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Informatique embarquée et objets connectés", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Name the arm’s joints and say what a servomotor does at each.
2. Explain the Arduino’s role between a command and a movement.
3. Trace one command from the user’s mouse, through the Tkinter window and the serial link, to the gripper.
4. Explain why the human is part of this control loop, and what the arm cannot do without them.

## What you need
Paper for the design parts. The full build needs the Braccio arm (or similar), an Arduino board and a computer with Python — the lesson is written to be learned from where the kit is absent.

## The run of the lesson (in order)
1. **Do it first** — Move your own arm to pick up a cup and list every joint movement and every decision your hand made without thinking — before the lesson gives each part to a motor or a program. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a robot arm with each joint circled and labelled and the Arduino at its foot wired to every servo — the student points at each joint and names its servo’s job
   - ADD GIF: a GIF of a slider being dragged in a window while the arm’s elbow bends in step — the student says which stage of the chain is acting at each moment of the GIF
   - ADD IMAGE: a picture of the chain from hand to gripper — window, cable, board, arm — with one arrow per stage — the student covers the labels and names every stage in order
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a robot arm with each joint circled and labelled and the Arduino at its foot wired to every servo → the student points at each joint and names its servo’s job
- GIF — a GIF of a slider being dragged in a window while the arm’s elbow bends in step → the student says which stage of the chain is acting at each moment of the GIF
- IMAGE — a picture of the chain from hand to gripper — window, cable, board, arm — with one arrow per stage → the student covers the labels and names every stage in order
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Expects the arm to "grab the cup" as one command → the arm knows only angles per servo; a grip is a choreography the human (or a recorded sequence) composes. Confuses the Arduino with the computer → the Python window runs on the computer and sends commands; the Arduino is the embedded board at the arm, driving the servos. Moves several sliders at once and loses the arm → one joint at a time, small angles, watching the arm — the interface is a control, not a game controller.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book builds this in the En codant strand of its embedded-systems theme — the Braccio arm driven through a Python (Tkinter/serial) HMI — the most complete sense–decide–act loop in the book; this lesson follows that build.
