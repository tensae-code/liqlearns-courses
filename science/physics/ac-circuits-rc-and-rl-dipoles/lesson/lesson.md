# AC circuits — RC and RL dipoles

## Do it first
Before you read: connect a battery, a resistor and a capacitor in series with a small lamp, and close the switch. A plain resistor circuit would snap the lamp on and keep it lit. This one does something stranger — the lamp glows, then **fades away** to nothing, though nothing in the circuit was switched off. The capacitor was filling up, and while it filled, the current shrank. A part that answers *gradually*, taking time, is going to answer a swinging current *out of step* — and that out-of-step answer is this whole lesson: what happens when alternating current meets a capacitor, and when it meets a coil.

## Sub lesson 1 — Alternating current and the dipole

Direct current (DC) flows one way, steady as a river. **Alternating current (AC)** flows back and forth: it rises, falls through zero, reverses, and repeats. One full back-and-forth is a **cycle**, the time for one cycle is the **period** T, and the number of cycles in a second is the **frequency** f = 1/T, measured in hertz (Hz). The mains supply in most of the world swings at 50 Hz — fifty full cycles every second, a period of 0.02 s. What a meter reads and what we quote (the 120 V or 230 V of a socket) is the **rms** value: the steady DC value that would do the same heating work.

Any part with two terminals that the current must pass through — a resistor, a capacitor, a coil, a lamp — is a **dipole**. On DC, a dipole is summed up by one number, its resistance R, and Ohm's law I = V/R closes the account. On AC that is no longer enough, for two reasons. First, a capacitor or a coil opposes an alternating current by an amount that depends on the *frequency* of the swing, not just on the part itself: that opposition is called **reactance**, written X and also measured in ohms. Second, the dipole can shift the current's timing against the voltage's timing: the **phase** difference. A complete AC account of a dipole therefore takes two numbers — how hard it opposes (its impedance, next sub lessons) and how far out of step it runs (its phase). The rest of this lesson earns those two numbers for the two dipoles that matter most: resistor-with-capacitor, and resistor-with-inductor.

## Sub lesson 2 — The RC dipole — the capacitor answers early

A capacitor is two plates separated by an insulator. On steady DC it charges up once and then blocks the current completely — your fading lamp. On AC there is no "once": the supply reverses every half-cycle, so the capacitor charges, discharges, charges the other way, and discharges again, forever. Charge keeps flowing onto and off the plates, and a real alternating current runs in the wires — the capacitor *passes* AC while blocking steady DC.

How hard does it oppose the swing? The faster the swing, the less charge piles up in each half-cycle, and the feebler the capacitor's push-back. Its reactance therefore *falls* as frequency rises:

**X_C = 1/(2πfC)**

with C in farads. In numbers: a 10 µF capacitor at 50 Hz has X_C = 1/(2 × π × 50 × 10 × 10⁻⁶) ≈ **318 Ω**. Double the frequency and the reactance halves.

Now the timing. The current is the flow of charge onto the plates — and the voltage across the capacitor is the *result* of the charge that has piled up. Flow first, pile-up after: the current does its work a quarter-cycle *before* the voltage peaks. In the RC dipole, **the current leads the voltage by 90°** (a quarter of a cycle).

Put a resistor and a capacitor in series across an AC supply. The same current passes through both; the resistor's voltage swings in step with the current, the capacitor's a quarter-cycle behind it. Two voltages a quarter-cycle apart do not add like plain numbers — they add like the sides of a right triangle, by squares. So the pair's total opposition, the **impedance**, is:

**Z = √(R² + X_C²)**, and the current is **I = V/Z**

Worked account: R = 300 Ω and X_C = 400 Ω give Z = √(300² + 400²) = √250,000 = **500 Ω**. Across a 10 V (rms) supply the current is 10/500 = **0.02 A**. Check by parts: the resistor carries V_R = IR = 6 V, the capacitor V_C = IX_C = 8 V, and 6² + 8² = 100 = 10² — the squares close the account that plain addition (6 + 8 = 14 V) would break. The phase of the pair sits between the two extremes: the current leads the supply voltage by an angle whose tangent is X_C/R — here tan φ = 400/300, so φ ≈ **53°**.

## Sub lesson 3 — The RL dipole — the inductor answers late

An inductor is a coil of wire, often wound on an iron core. Its nature is to fight *change*: when the current tries to rise, the coil's own magnetic field induces a back-EMF that pushes against the rise; when the current tries to fall, the back-EMF pushes to keep it going (you met this as self-induction in the induction lesson). On DC the fight is over in a moment and the coil is nearly a plain wire. On AC the current changes without rest, so the fight never ends — the coil opposes the alternating current itself.

The faster the swing, the faster the change the coil must fight, and the stronger its push-back. Its reactance therefore *rises* with frequency — the exact opposite of the capacitor's:

**X_L = 2πfL**

with L in henrys. In numbers: a coil of 0.1 H at 50 Hz has X_L = 2 × π × 50 × 0.1 ≈ **31.4 Ω**. Double the frequency and the reactance doubles.

The timing follows from the fight: because the coil resists every change, the current is always catching up with the voltage that drives it. In the RL dipole, **the current lags the voltage by 90°** (a quarter of a cycle).

A resistor and an inductor in series combine exactly as the RC pair did — same current, part-voltages a quarter-cycle apart, squares adding:

**Z = √(R² + X_L²)**, and **I = V/Z**

Worked account: R = 40 Ω and X_L = 30 Ω give Z = √(40² + 30²) = **50 Ω**. Across a 100 V supply the current is 100/50 = **2 A**; the parts carry V_R = 80 V and V_L = 60 V, and 80² + 60² = 100² as they must. The current lags the supply voltage with tan φ = X_L/R = 30/40, φ ≈ **37°**.

This account is measurable, exactly as Haiti's programme places it — with a multimeter on an AC supply (school work uses a low-voltage supply, never the socket itself): measure the supply voltage and the voltage across each part of a series dipole, and the squares check, V² = V_R² + V_X², either confirms your impedance or sends you back to find the mistake. The two dipoles are mirror images: the capacitor answers early and softens as the swing quickens; the inductor answers late and stiffens. Between them they run the AC world — the filters that sort frequencies, the ballasts and chokes that tame lamps and motors, and the tuned circuits that pick one radio station out of the air.

## The key ideas

- **AC** swings back and forth: frequency f = 1/T, and quoted voltages are **rms** values. A **dipole** is any two-terminal part; on AC it is described by its opposition *and* its **phase**, not by resistance alone.
- **Capacitive reactance X_C = 1/(2πfC)** — falls as frequency rises. In the RC dipole the **current leads the voltage by 90°**, because charge must flow before the capacitor's voltage can build.
- **Inductive reactance X_L = 2πfL** — rises as frequency rises. In the RL dipole the **current lags the voltage by 90°**, because the inductor fights every change of current.
- A resistor in series with either part gives **impedance Z = √(R² + X²)** and current **I = V/Z**; the part-voltages add by squares, **V² = V_R² + V_X²** — the multimeter check of the whole account.

## Say it to your companion
Tell your companion the whole story in order: the lamp that faded on DC because the capacitor filled; AC's endless charge-and-discharge that lets a capacitor pass a swinging current; the reactance that falls for a capacitor and rises for a coil as the swing quickens; who leads and who lags, and why; and one full impedance account priced in numbers and checked by squares. If your companion can say why 6 V across the resistor and 8 V across the capacitor sit happily on a 10 V supply, the lesson has landed.

## Do It Yourself
1. Find the reactance of a 47 µF capacitor at 50 Hz, and say — in one sentence — what its reactance would do if the supply were changed to 100 Hz.
2. A series RL dipole has R = 60 Ω and a coil of reactance X_L = 80 Ω, connected across a 50 V AC supply. Find the impedance, the current, the voltage across each part, and check your voltages by squares.
3. A multimeter measures a series RC dipole on a low-voltage AC supply: the supply reads 13 V, the resistor reads 5 V and the capacitor reads 12 V. Show that the readings agree, and say which wave — current or voltage — is ahead in this dipole, and by how much of a cycle at most.
