# The oscillating LC circuit and electrical resonance

## Do it first
One aerial wire carries every station in the city at once, all mixed together as one buzzing signal. Yet turning one knob lifts a single voice cleanly out of the mixture. Inside the radio, the knob turns a capacitor across a coil — and this lesson is the physics of why that pair, set right, hears one frequency and ignores the rest.

## Sub lesson 1 — Energy swapping between capacitor and coil

Charge a capacitor, disconnect the supply and connect it across an inductor. The capacitor discharges through the coil: as its charge and electric-field energy fall, the coil's current and magnetic-field energy rise. When the capacitor is empty the current is greatest — and does not stop, because the coil's inductance keeps it flowing, recharging the capacitor with the opposite polarity. Then the discharge runs backwards. The energy sloshes from capacitor to coil and back, electric to magnetic to electric, twice per cycle.

In a perfect circuit (no resistance) the sloshing would run forever at constant amplitude — an electrical pendulum. Real circuits lose a little energy as heat in the wires each cycle, so the oscillations die away (damping) unless a source feeds energy back in step — which is precisely what an oscillator circuit arranges.

## Sub lesson 2 — The natural frequency of the LC circuit

The trade has one natural rate, set by the two components alone: f = 1/(2π√(LC)) — the same shape as the pendulum's law, with inductance playing the mass (reluctance to change current) and capacitance the springiness (reluctance to change voltage). Double L or C and the frequency falls by √2; the oscillation's period is T = 2π√(LC).

At every instant of the cycle the account holds: Q²/2C (energy in the capacitor) + ½LI² (energy in the coil) = constant. When the charge is maximum the current is zero; a quarter-period later the charge is zero and the current maximum. Frequency depends on neither the starting charge nor the current's size — the LC circuit keeps its own time, like a pendulum, whatever amplitude it swings at.

## Sub lesson 3 — Resonance and the tuned radio circuit

Connect the LC pair to the aerial. Every station's signal pushes tiny currents at its own frequency through the circuit — but the circuit answers strongly only to the push arriving at its own natural frequency: electrical resonance. At that one frequency the response builds up large (limited only by the circuit's resistance), giving a usable signal; all other frequencies are answered feebly and are rejected.

Tuning is nothing but setting f to the station: turning the knob rotates a variable capacitor, changing C until 1/(2π√(LC)) equals the wanted carrier frequency. This resonant circuit is the gatekeeper of every radio and television receiver — selection by resonance, before any amplification begins. The sharpness of the selection (how completely neighbours are rejected) improves as the circuit's resistance falls — a high-quality, low-loss tuned circuit rings narrow and true.

## The key ideas

- An LC circuit oscillates by trading energy: capacitor's field energy Q²/2C ↔ inductor's magnetic energy ½LI², the sum constant in the ideal circuit.
- The natural frequency is f = 1/(2π√(LC)) — set by L and C alone, independent of amplitude; resistance damps the oscillation away.
- At resonance the circuit responds strongly to a driving signal at its own frequency and feebly to all others.
- A radio tunes by varying C (or L) until the LC frequency equals the wanted station's carrier — resonance is the receiver's gatekeeper.

## Say it to your companion
Tell your companion the whole lesson in order, in your own words — start with the opening activity, then take each sub lesson in turn and finish with what it is used for. If your companion can repeat the main idea back to you, the lesson has landed.

## Do It Yourself
1. An LC circuit has L = 2 mH and C = 500 pF. Calculate its natural frequency, showing the formula and the unit care it needs.
2. To receive a station at twice the frequency of question 1's setting with the same coil, by what factor must the capacitance be changed? Justify from the formula.
3. Two receivers are tuned to the same station; one has much lower resistance in its tuned circuit. Whose tuning is sharper, and what happens to the free oscillation of each circuit when its aerial signal is removed?
