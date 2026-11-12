# Alternating-current circuits — reactance, impedance and resonance

## Do it first
Before you read: a radio tuner turns and one station rises out of the noise while its neighbours fade. Nothing in the aerial changed — a circuit inside was walked to the one frequency where it answers strongly. That behaviour — frequency deciding how hard a circuit pushes back, and a special frequency where the pushback collapses — is this lesson: reactance, impedance and resonance.

## Sub lesson 1 — Alternating current and the alternator

An **alternator** — a coil rotating in a magnetic field — generates EMF that reverses sinusoidally: e = e₀·sin(ωt), with angular frequency ω = 2πf. Mains current is this current: its direction reverses f times per second (50 Hz in most of the world), and its quoted voltage is the **RMS** (effective) value — the DC voltage that would deliver the same power — with the peak √2 times larger. In a pure resistor the current follows the voltage in step (**in phase**), and power is dissipated as in DC. Capacitors and inductors break that step, and everything in this lesson follows from how they break it.

## Sub lesson 2 — Reactance — the frequency-dependent opposition

A **capacitor** in an AC circuit charges and discharges each half-cycle: current flows while charge accumulates, leading the voltage by 90°. Its opposition, **capacitive reactance X_C = 1/(2πfC)**, *falls* as frequency rises (at high frequency the plates barely charge before the voltage reverses) and blocks DC entirely. An **inductor** opposes changes of current with a back-EMF: its current *lags* the voltage by 90°, and its **inductive reactance X_L = 2πfL** *rises* with frequency. Neither reactance dissipates energy on average — energy is borrowed and returned each cycle, stored in the capacitor's electric field and the inductor's magnetic field — unlike resistance, which dissipates it for good.

## Sub lesson 3 — Impedance and resonance

In a series RLC circuit the resistor's voltage is in phase with the current while the reactances' voltages stand 90° either side, so the parts add as a right triangle: the **impedance Z = √(R² + (X_L − X_C)²)**, with I = V/Z and the phase of the whole circuit set by which reactance wins. One frequency makes the reactances cancel exactly, X_L = X_C: the **resonance frequency f₀ = 1/(2π√(LC))**. There Z falls to its minimum — just R — the current peaks, and the circuit selects that frequency out of all others: the radio tuner's trick, and also a hazard in power systems, where unwanted resonance can drive currents and voltages far beyond design. Sharpness of the peak is the circuit's quality factor; a sharp resonance selects narrowly, a broad one gently.

## The key ideas

- AC from an alternator is sinusoidal; quoted values are **RMS** (peak ÷ √2), and only the resistor keeps current and voltage in phase.
- **Reactance**: X_C = 1/(2πfC) (current leads voltage 90°, falls with f, blocks DC) and X_L = 2πfL (current lags 90°, rises with f); reactance stores and returns energy, resistance dissipates it.
- **Impedance** of series RLC: Z = √(R² + (X_L − X_C)²), I = V/Z — the parts combine by the right-triangle rule because of their phases.
- **Resonance** at f₀ = 1/(2π√(LC)): X_L = X_C, Z = R minimum, current maximum — frequency selection, from radio tuning to power-system hazard.

## Say it to your companion
Tell your companion: how an alternator's EMF behaves and what RMS means; how capacitor and inductor each treat current's phase and how their reactances move with frequency — oppositely; how impedance combines the three parts and why the combination is a right triangle; and what resonance is, its formula, and its two faces — tuner and hazard. If your companion can say why raising frequency helps current through a capacitor but hinders it through an inductor, the lesson has landed.

## Do It Yourself
1. A 10 µF capacitor sits on 50 Hz mains. Find its reactance X_C. (Use X_C = 1/(2πfC).)
2. A series circuit has R = 30 Ω, X_L = 80 Ω and X_C = 40 Ω. Find Z and, on a 230 V RMS supply, the current.
3. An LC pair has L = 0.10 H and C = 10 µF. Find the resonance frequency f₀ = 1/(2π√(LC)) and say what the impedance is there if R = 5 Ω.
