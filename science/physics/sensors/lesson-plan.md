# Lesson plan — Sensors

**Course:** Science · **Title:** Physics · **Lesson:** Sensors
**Place in the curriculum:** Physics (CURRICULUM.md Unit 18), inside the electronics topic of Vietnam's study-topics book — before Amplifiers and switches and Electronics in daily life: the input side of every electronic system
**The one thing this lesson teaches:** a sensor is a device that turns a physical quantity — light, temperature, strain, pressure, magnetism — into an electrical signal a circuit can use: its resistance, voltage or current changes in a known way as the quantity changes, and a useful sensor is judged by its sensitivity (how much signal per unit change), its range, and how fast and repeatably it responds
**This lesson's own level:** it stands on its own — a learner can land here directly. Any earlier lesson named below is recommended first, never forced

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. Images follow the picture rule (a real photograph, or real art, with its source). GIFs come first where a thing must be shown moving or popping — a GIF here is 1–2 seconds.

## Sub lessons
1. **What a sensor is — the circuit's senses** — Every electronic system that reacts to the world begins with a **sensor** (Vietnamese: cảm biến): a component whose electrical property tracks a physical quantity. The **thermistor** changes resistance with temperature; the **LDR** (light-dependent resistor) changes resistance with light; the **strain gauge** changes resistance as it is stretched; piezoelectric crystals make a voltage when squeezed; a Hall sensor answers a magnetic field. The pattern is universal: **quantity in → electrical signal out**, in a known, repeatable proportion (or at least a known curve). Vietnam's Grade 11 study-topics book introduces electronics through its senses first (Bài 7, Cảm biến): sensors as a standalone lesson before the op-amp that will amplify their whispers.
2. **The working members — and how each speaks** — Each family speaks a different electrical dialect. **Resistive** sensors (thermistor, LDR, strain gauge) are read in a **potential divider**: their changing resistance moves the divider's output voltage up and down with the quantity — falling light raises an LDR's resistance and swings the divider's voltage, which a later stage compares or amplifies. **Generating** sensors (thermocouple, piezoelectric, photovoltaic cell) make their own small voltage or current — no supply needed for the sensing itself, but the signal is tiny and begs amplification. Vietnam's lesson surveys the types and their characteristics together, as a buyer would: what it senses, how it speaks, how big its voice is.
3. **Judging a sensor — sensitivity, range, response** — Three characteristics decide whether a sensor fits a job. **Sensitivity**: the size of the signal change per unit change of the quantity — a gauge that moves 1 mV per degree against one that moves 10 mV per degree. **Range**: the span of the quantity it can follow before saturating or breaking. **Response time and repeatability**: how fast it follows a change, and whether the same quantity always earns the same signal (drift and hysteresis are the enemies). Vietnam's lesson names these as the sensor's characteristics (đặc tính) — the vocabulary with which the sensor circuits of Bài 8–9 are then designed: sensor chosen, divider set, op-amp switched output — a complete sensing system assembled from the topic's three lessons.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- This lesson stands alone for a learner landing on it directly; anything that would help is explained inside it as it is needed.

## What the learner can do when it ends
1. Define a sensor and name five, with the quantity each senses.
2. Explain how a potential divider reads a resistive sensor.
3. Give one generating sensor and say why its signal usually needs amplification.
4. Judge a sensor choice for a job using sensitivity, range and response.

## What you need
An LDR or thermistor and a multimeter if the class has them; otherwise a phone's light sensor and a free sensor app for the hands-on.

## The run of the lesson (in order)
1. **Do it first** — the learner does the opening activity before any explanation (lesson/lesson.md).
2. **The explanation** — the lesson's parts, in order (lesson/lesson.md).
   - ADD IMAGE: a picture of a panel of four sensors drawn as circuit components with their quantities as icons — a thermistor beside a thermometer, an LDR beside a sun, a strain gauge bonded to a bending beam, a piezoelectric disc under a pressing arrow — each wired into a small potential-divider or output line labelled with its electrical signal [Picture 36737] — the student studies the picture and names what each part shows.
   - ADD GIF: a 1–2 second GIF of the lesson's central change happening — the student watches and says what changed
   - ADD AUDIO (described slot only — no audio file is made in this build): a voice reading the lesson's key ideas aloud — the student listens, then repeats each one aloud from memory.
3. **Say it to your companion** — the learner explains the lesson's main ideas in their own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson told in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer and fill-in-the-blank — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — as described above → the student studies the picture and does what its line says.
- GIF — as described above → the student watches the change happen.
- AUDIO (described slot only) — a voice reading the key ideas aloud → the student repeats each from memory.
- VIDEO — the video-script filmed (made later) → the student watches and does the lesson's actions along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Cannot start → return to Do it first and do the opening activity with real objects before reading any explanation; the explanation is the story of that activity.
- Mixes the sub lessons up → re-read the key ideas in order; each key idea is one sub lesson compressed to a line.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
