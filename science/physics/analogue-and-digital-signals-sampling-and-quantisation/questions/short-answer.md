# Analogue and digital signals — sampling rate and sampling precision — short answer

Answer in a sentence or two.

**1.** (Sub lesson 1) Explain why sampling a signal too slowly can invent a wave that was never there.
**Answer: If reads are taken less than twice per cycle of the fastest component, the stored points fit a slower wave just as well — reconstruction follows the points and produces that false slow wave (aliasing); the true fast changes between samples were never recorded.**

**2.** (Sub lesson 1) Why does CD audio use a sampling rate of 44.1 kHz?
**Answer: Hearing reaches about 20 kHz; the rule requires sampling at least twice the highest frequency to be kept — 2 × 20 kHz = 40 kHz — and 44.1 kHz sits just above that minimum.**

**3.** (Sub lesson 2) What two errors are the price of analogue-to-digital conversion, and what reduces each?
**Answer: Sampling error, reduced by sampling faster; quantisation error, reduced by using more bits per sample (more, finer levels).**

**4.** (Sub lesson 2) What is an embedded system, and why does it depend on AD and DA conversion?
**Answer: An embedded system is a small dedicated computer built into a device; it senses an analogue world (AD conversion in) and acts on it (DA conversion out), so the quality of both conversions bounds what it can know and do.**
