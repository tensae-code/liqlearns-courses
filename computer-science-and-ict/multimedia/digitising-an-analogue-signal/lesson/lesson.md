# Digitising an Analogue Signal

## Do it first

Sing one long note and slide it slowly upward. The pitch moved smoothly — through every frequency between start and finish, with no steps. That smoothness is what **analogue** means: a signal that varies continuously and can take any value. A microphone turns your voice into just such a signal — a voltage that rises and falls smoothly with the sound. But a computer stores separated, counted things: bits, levels, codes. Turning the smooth signal into counted form — **digitising** it — is a three-step craft: sampling, quantisation and coding. Montenegro's book teaches it at the end of the climb, where circuits meet the real world's signals, and every recording you have ever heard passed through these three steps.

## Sub lesson 1 — Sampling — measuring at regular instants

You cannot store a smooth wave whole, so you do what a film does with motion: take **snapshots**. **Sampling** means measuring the signal's value at evenly spaced instants — say, every thousandth of a second — and keeping only those measured values. Between two samples, the wave did whatever it did unrecorded; the digital copy will connect the samples and trust that nothing important hid between them.

How often the snapshots come is the **sampling rate** (or sampling frequency), counted in samples per second — in hertz, Hz. The governing rule is the **sampling theorem**, associated with Nyquist: **the sampling rate must be at least twice the highest frequency present in the signal.** Sample slower than that and fast wiggles slip between snapshots and come back disguised as slower wiggles that were never there — an error called **aliasing**, the same lie that makes wagon wheels seem to turn backwards in films.

[Picture — one smooth wave drawn three times: sampled densely, its samples hugging the curve; sampled at the Nyquist limit, just following it; sampled too sparsely, its samples sketching a false slow wave through them]

Real numbers make it concrete. Human hearing reaches about 20 kHz, so CD audio samples at **44.1 kHz** — just above twice 20 kHz. A telephone voice, where only intelligibility matters, is sampled at 8 kHz and sounds thin but clear. Rate is a bargain: more samples per second, a truer copy — and a bigger file, as the last step will count.

## Sub lesson 2 — Quantisation and coding — levels, bits and the size of the copy

A sample's measured value is a smooth number — 0.637 of full volume, say — and smooth numbers are exactly what we cannot store. **Quantisation** rounds each sample to the **nearest of a fixed ladder of levels**. If the ladder has 256 rungs, the sample becomes 'the 163rd rung', and the small distance between the true value and the rung is lost forever: that loss is **quantisation error**, and in sound it is heard as a faint background noise under the music.

The ladder's fineness is set by the **bit depth** — how many bits code each sample. n bits give **2ⁿ levels**: 8 bits give 256 levels, 16 bits give 65 536. More bits, smaller steps, quieter error, truer copy — and a bigger file. CD audio chose 16 bits; old telephone and early computer sound made do with 8, and you can hear the graininess the missing levels leave behind.

[Picture — a staircase of quantisation levels drawn over a smooth curve: each sample snapped to its nearest rung, the small gaps between curve and rung marked as the error]

Then the last step is the one this whole climb has practised: **coding**. Each sample is now just a level number, and the level number is written in binary — 8 or 16 bits per sample, one code after another, a stream of bits that *is* the digitised signal. And now the copy's cost can be counted exactly: **size = sampling rate × bit depth × seconds** (per channel). One minute of CD sound, one channel: 44 100 × 16 × 60 ≈ 42 million bits ≈ 5.3 megabytes; stereo doubles it. Every choice in digitising is the same three-way bargain — rate, depth, size — struck against how true the copy must be.

## Say it to your companion

Tell your companion, in your own words: digitising turns a smooth analogue signal into bits in three steps — sampling measures it at regular instants at a rate at least twice its highest frequency; quantisation rounds each measure to the nearest of 2ⁿ levels set by the bit depth, losing a little as quantisation error; coding writes each level in binary, and the file's size is rate times depth times seconds. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what sampling is and what the sampling rate measures, in hertz. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: state the sampling theorem — sample at least twice the highest frequency — and name the error (aliasing) that breaks it. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: say what quantisation is, how bit depth sets the number of levels as 2ⁿ, and what quantisation error is. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: describe coding as the final step and compute a digitised recording's size from rate × depth × seconds. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
