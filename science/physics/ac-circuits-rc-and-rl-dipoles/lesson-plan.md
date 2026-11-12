# Lesson plan — AC circuits — RC and RL dipoles

**Course:** Science · **Title:** Physics · **Lesson:** AC circuits — RC and RL dipoles
**Place in the curriculum:** Physics (CURRICULUM.md Unit 18), beside the AC and electronics lessons — Transformers — stepping voltage up and down, Capacitor networks and stored energy and the rectification lessons: this is the lesson where alternating current meets the two components that answer it out of step, the capacitor and the inductor
**The one thing this lesson teaches:** in an alternating-current circuit, a resistor is not the whole story — a capacitor and an inductor each oppose the current with a **reactance** that depends on the frequency, and each shifts the current out of step with the voltage (the **phase**): current leads through a capacitor, lags through an inductor, and the pair's combined opposition is the **impedance** Z = √(R² + X²)
**This lesson's own level:** it stands on its own — a learner can land here directly. Capacitors — storing charge, Current, voltage, resistance — Ohm's law and Transformers — stepping voltage up and down are recommended first, never forced

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. Images follow the picture rule (a real photograph, or real art, with its source). GIFs come first where a thing must be shown moving or popping — a GIF here is 1–2 seconds.

## Sub lessons
1. **Alternating current and the dipole** — AC swings back and forth (period, frequency, the mains), and a **dipole** is any two-terminal part the current must pass through; with AC the honest measure of a dipole is not resistance alone but how much it opposes the swing and how far it shifts the current's timing — its phase
2. **The RC dipole — the capacitor answers early** — a capacitor in AC charges and discharges every half-cycle: it passes alternating current while blocking steady DC, opposes it with capacitive reactance X_C = 1/(2πfC), and the current **leads** the voltage by a quarter-cycle (90°); a resistor and capacitor in series combine into impedance Z = √(R² + X_C²)
3. **The RL dipole — the inductor answers late** — an inductor fights every change of current (its back-EMF), opposes AC with inductive reactance X_L = 2πfL, and the current **lags** the voltage by a quarter-cycle (90°); a resistor and inductor in series combine into impedance Z = √(R² + X_L²) — and a multimeter on a low-voltage AC supply reads the voltages that prove the impedance account

## Before this lesson
- Recommended first: **Capacitors — storing charge**, **Current, voltage, resistance — Ohm's law** and **Transformers — stepping voltage up and down**. Recommended, never forced.

## What the learner can do when it ends
1. Say, in their own words: what a dipole is, and why AC needs reactance and phase where DC needed only resistance.
2. Work the reactances in numbers: X_C = 1/(2πfC) and X_L = 2πfL, and say how each changes when the frequency rises.
3. State the phase in each dipole: current leads voltage in the RC dipole, lags it in the RL dipole — and say why, from the component's own behaviour.
4. Price a series dipole: Z = √(R² + X²), then the current I = V/Z from the supply voltage, and check the account with the voltages across each part (V² = V_R² + V_X²).
5. Answer the lesson's questions from the lesson text alone.

## What you need
For the hands-on: a low-voltage AC source (a small transformer's output — never the mains socket itself), a multimeter, a resistor, a capacitor and a coil of wire around an iron core, connecting leads — plus a battery, a resistor, a capacitor and a small lamp or LED for the charging-time activity, and the lesson's worked numbers, which carry the dipoles where apparatus is not available.

## The run of the lesson (in order)
1. **Do it first** — the learner does the opening activity before any explanation (lesson/lesson.md).
2. **The explanation** — the lesson's parts, in order (lesson/lesson.md).
   - ADD IMAGE: a picture of two oscilloscope traces on one screen, the voltage wave and the current wave drawn as two sine waves shifted by a quarter of a cycle, the current's peak arriving first — the student points to which wave leads and says by how much of a cycle.
   - ADD GIF: a 1–2 second GIF of a capacitor's plates charging and discharging in rhythm with a swinging AC source, the charge piling up and draining away twice in every full swing — the student watches the plates empty exactly when the source's push reverses.
   - ADD AUDIO (described slot only — no audio file is made in this build): a voice reading the lesson's key ideas aloud — the student listens, then repeats each one aloud from memory.
3. **Say it to your companion** — the learner explains the lesson's main ideas in their own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson told in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer and fill-in-the-blank — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — two sine traces, voltage and current, shifted by a quarter-cycle → the student studies the picture and names which wave leads.
- GIF — a capacitor charging and discharging in rhythm with the AC swing → the student watches the change happen.
- AUDIO (described slot only) — a voice reading the key ideas aloud → the student repeats each from memory.
- VIDEO — the video-script filmed (made later) → the student watches and does the lesson's actions along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Cannot start → return to Do it first: the lamp on the charging capacitor fades instead of snapping off. Hold that slowness; the lesson is its AC form.
- Mixes up who leads → the capacitor's current must flow *before* its voltage can build (charge first, voltage after), so current leads in RC; the inductor fights change, so its current is always catching up — current lags in RL.
- Adds R and X like plain numbers → the two voltages are a quarter-cycle apart, so they add like the sides of a right triangle: squares first, then the root. Resistors and reactances never simply add.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
