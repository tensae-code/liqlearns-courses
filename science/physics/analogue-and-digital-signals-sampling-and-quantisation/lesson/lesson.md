# Analogue and digital signals — sampling rate and sampling precision

## Do it first
Before you read: a vinyl record holds a groove that wiggles exactly as the sound wiggled — every instant is stored. A CD holds only numbers, about 44 thousand of them per second per channel. Between two of those numbers, the sound did something — and the CD does not know what. Why does the CD still sound complete? Keep the question: how often must you read a changing signal, and how finely must you write each reading down, before the numbers can rebuild the signal?

## Sub lesson 1 — Sampling — reading a smooth signal at instants

An **analogue** signal changes continuously: at every instant it has a value, and between any two instants it takes every value in between. A digital system cannot store that infinity, so an **analogue-to-digital (AD) converter** first **samples** the signal — it reads the value at regular instants and ignores everything between. The **sampling rate** (sampling frequency) counts the reads per second, in hertz. Sampling always throws information away, and the loss has a shape: sample too slowly and the fastest changes slip between reads — the stored numbers can even suggest a false, slower wave that was never there (**aliasing**, the extreme form of **sampling error**). The working rule of the Grade 13 book's conversion chapter: the sampling rate must be **at least twice the highest frequency** that must be kept. Human hearing ends near 20 kHz, so CD audio samples at **44.1 kHz** — just over twice the fastest change the ear can hear.

[Picture 36712]

## Sub lesson 2 — Quantisation and converters — how fine the numbers are

A sampled value is still a measurement with endless decimals; the converter must round it to one of the levels it can store. That rounding is **quantisation**, and the **sampling precision** — the number of **bits** per sample — fixes how many levels exist: 8 bits give 2⁸ = 256 levels, 16 bits give 2¹⁶ = 65,536 levels. More levels mean a smaller step between them and a smaller **quantisation error** — at the price of more numbers to store. The **AD converter** performs sampling and quantisation together on the way in; the **DA converter** runs the doorway backwards, rebuilding a smooth signal from the stored numbers on the way out. Around the converters sit **embedded systems** — small dedicated computers built into devices — which sample sensors, decide, and drive outputs: every one of them lives by this conversion, and its quality is set by the two numbers of this lesson — how often it samples, and how finely.

## The key ideas

- Sampling reads a continuous signal at regular instants; the sampling rate is measured in hertz
- Sample too slowly and information is lost — sampling error, and in the extreme, aliasing (a false slower wave)
- Rule: sample at least twice as fast as the highest frequency to be kept (CD audio: 44.1 kHz for 20 kHz hearing)
- Quantisation rounds each sample to one of 2^n levels, n = bits of sampling precision; more bits = smaller quantisation error; AD converts in, DA converts out, embedded systems live by both

## Say it to your companion
Tell your companion: a digital machine stores a signal as numbers taken at sampled instants and rounded to quantisation levels — fast enough sampling and fine enough levels rebuild the signal; slow or coarse ones bake the error in. If your companion can work the Do It Yourself tasks without looking back, the lesson has landed.

## Do It Yourself
1. A signal contains frequencies up to 8 kHz. What is the slowest sampling rate that can keep it, and what goes wrong at 10 kHz sampling?
2. A converter's precision rises from 8 bits to 16 bits. How many times more quantisation levels does it have, and what happens to the quantisation error and to the storage needed?
3. A temperature sensor in an embedded system samples once an hour; a microphone front-end samples 44,100 times a second. Explain, from the lesson's rule, why both rates can be right.
