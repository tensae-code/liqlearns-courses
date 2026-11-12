# The microphone and radio receiver circuits

## Do it first
Before you read: speak into any phone or recorder and watch the level bar dance as your voice rises and falls — something inside has already turned your sound into an electric pattern that copies it. Then turn to a radio: dozens of stations are arriving at the aerial at this moment, yet you hear one. This lesson follows the whole chain — how sound becomes current at the microphone, and how a receiver picks one station out of the crowd and takes its sound back off the carrier.

## Sub lesson 1 — The microphone — sound becomes a copying current

A microphone's job is translation: sound in, electrical signal out, with the pattern preserved. In the moving-coil (dynamic) microphone, the sound waves strike a light **diaphragm**, which vibrates in step with the sound — loud sounds push it further, high notes shake it faster. The diaphragm carries a small **coil** sitting in the field of a permanent magnet; as the coil moves with the diaphragm, the magnetic flux through it changes and an **induced current** flows in the coil (electromagnetic induction at work). That current rises and falls exactly as the sound does — strong when the sound is strong, rapid when the note is high — so the electrical signal is a faithful copy of the sound wave. This current is the audio signal that, at a transmitter, will modulate a carrier, and the loudspeaker at the journey's end is the microphone run backwards: varying current in a coil, diaphragm moved, sound out.

## Sub lesson 2 — The resonance circuit — choosing one station

Every station within reach delivers its carrier to the aerial together, and the receiver's first job is selection. The **tuning circuit** is a coil and a **variable capacitor** in combination — an LC circuit — which **resonates** at one frequency: f set by the coil's inductance and the capacitor's value. At its resonant frequency the circuit responds strongly to that one carrier and weakly to all others, exactly as a swing answers pushes at its own natural frequency and ignores others. Turning the tuning knob changes the capacitance, sliding the resonant frequency along the band until it lands on the station you want. Only that station's modulated carrier passes on in strength; the rest of the crowd is turned away at this gate. Resonance here is not a curiosity — it is the single idea that makes broadcasting to many listeners on many stations possible at all.

## Sub lesson 3 — The detector circuit — taking the sound off the carrier

The tuned signal is still a high-frequency carrier wearing the audio as a pattern; no loudspeaker could follow the carrier itself, and no ear could hear it. The **detector** (demodulator) strips the carrier away: a **diode** — a one-way gate for current — passes only one half of the modulated wave, and a smoothing capacitor holds the tops of the waves, tracing out the **envelope**, which is the original audio pattern (in AM, the amplitude pattern; the varying current recovered is the audio signal). What remains is the same kind of varying current the microphone made, much weakened by its journey. An **amplifier** strengthens it, and the loudspeaker converts it back to sound. Read the chain end to end: aerial → resonance circuit selects → detector separates → amplifier strengthens → loudspeaker speaks. Every radio, however modern its parts, still does these four jobs in this order.

## The key ideas

- A moving-coil microphone turns sound into a varying current by induction: the diaphragm's coil moves in a magnetic field, and the induced current copies the sound's pattern
- The tuning circuit is an LC resonance circuit — turning the variable capacitor slides its resonant frequency onto one station's carrier and rejects the rest
- The detector uses a diode and smoothing to strip the carrier away and recover the audio envelope
- The recovered audio is amplified and the loudspeaker — a microphone in reverse — turns it back into sound

## Say it to your companion
Tell your companion: A moving-coil microphone turns sound into a varying current by induction: the diaphragm's coil moves in a magnetic field, and the induced current copies the sound's pattern; The tuning circuit is an LC resonance circuit — turning the variable capacitor slides its resonant frequency onto one station's carrier and rejects the rest; The detector uses a diode and smoothing to strip the carrier away and recover the audio envelope; The recovered audio is amplified and the loudspeaker — a microphone in reverse — turns it back into sound. If your companion can work the Do It Yourself numbers without looking back, the lesson has landed.

## Do It Yourself
1. A receiver is tuned away from any station and only hiss is heard. Explain, using the resonance circuit, what the tuning knob is actually changing and why no station's audio reaches the detector in strength.
2. A microphone's diaphragm is punctured and stiff. Predict two faults in the electrical signal it produces — one for loud sounds and one for high notes — and justify each from how the microphone works.
3. Put the stages in order and give each its job: amplifier, detector, loudspeaker, resonance circuit. Then say which single stage, if removed, would leave a strong signal of every station mixed together.
