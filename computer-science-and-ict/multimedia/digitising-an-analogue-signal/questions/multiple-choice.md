# Digitising an Analogue Signal — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) Sampling a signal means —**
a) Turning it up louder  b) Measuring its value at evenly spaced instants and keeping only those measurements  c) Rounding it to levels  d) Writing it in binary
**Answer: b) Measuring its value at evenly spaced instants and keeping only those measurements** — Sampling is the first step: snapshots in time. Rounding is quantisation; binary writing is coding.

**2. (Sub lesson 1) The sampling theorem requires the sampling rate to be at least —**
a) Equal to the highest frequency  b) Twice the highest frequency in the signal  c) Ten times the highest frequency  d) 44.1 kHz always
**Answer: b) Twice the highest frequency in the signal** — Below twice the highest frequency, aliasing invents patterns that were never in the signal.

**3. (Sub lesson 1) CD audio's 44.1 kHz rate is chosen because human hearing reaches about —**
a) 2 kHz  b) 10 kHz  c) 20 kHz  d) 100 kHz
**Answer: c) 20 kHz** — 44.1 kHz is just above twice 20 kHz — the Nyquist rule applied to the top of hearing.

**4. (Sub lesson 2) Quantisation error is —**
a) A wiring fault  b) The small loss when each sample is rounded to the nearest level, heard as noise  c) The file becoming too large  d) Aliasing
**Answer: b) The small loss when each sample is rounded to the nearest level, heard as noise** — The true value between rungs cannot be kept; that rounding gap is quantisation error, reduced (never removed) by more bits.

**5. (Sub lesson 2) A bit depth of 12 bits gives how many quantisation levels?**
a) 12  b) 144  c) 1024  d) 4096
**Answer: d) 4096** — Levels = 2ⁿ: 2¹² = 4096 levels.

**6. (Sub lesson 2) One channel is digitised at 20 kHz with 8-bit depth for 5 seconds. The copy's size is —**
a) 28 000 bits  b) 800 000 bits  c) 160 000 bytes exactly with nothing else counted  d) 8 000 bits
**Answer: b) 800 000 bits** — Size = rate × depth × seconds = 20 000 × 8 × 5 = 800 000 bits (100 000 bytes).
