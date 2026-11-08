# Monte Carlo and Simulation — short answer

Sub-lesson markers (2026-11-08 restructure): every item's marker names the sub lesson it belongs to. The files' old depth groups map onto the sub lessons as: (Level 1) -> Sub lesson 1 — Random Numbers and Digits · (Level 2) -> Sub lesson 2 — The Congruential Generator and PPS Ranges · (Level 3) -> Sub lesson 3 — Monte Carlo and Testing a Model.

Answer in a word or a short line.

**1. (Sub lesson 1)** Why is a congruential generator's output called pseudo-random?
**Answer:** It only looks random — one seed and one rule rebuild the whole run exactly (Pakistan, Ch. 7).

**2. (Sub lesson 1)** What must be fixed in writing before a table simulation starts?
**Answer:** The reading rule: direction, grouping, and what each digit (or block) means as an outcome (Pakistan, Ch. 7, Table 7.1 use).

**3. (Sub lesson 2)** Write the congruential rule.
**Answer:** xₙ₊₁ = a·xₙ + b (mod m) (Pakistan, Ch. 7).

**4. (Sub lesson 2)** With seed 5, a = 13, b = 0, m = 16, the fourth value returns to 5. What does that force?
**Answer:** The whole cycle repeats from there — the sequence has period 4 (1, 13, 9, 5).

**5. (Sub lesson 2)** Probabilities are 0.5, 0.3, 0.2. Give the PPS stretches over 00–99.
**Answer:** 50 numbers, 30 numbers, 20 numbers — e.g. 00–49, 50–79, 80–99 (Pakistan, Ch. 7).

**6. (Sub lesson 3)** China's Monte Carlo section sits inside which larger topic (§10.3)?
**Answer:** Frequency and probability — §10.3.2, random simulation, at p.255.

**7. (Sub lesson 3)** The Mendel reading is filed as what kind of material, and how does this lesson word it?
**Answer:** As a reading — and the lesson words it as a reading: a model held up against real counts (China, pp.259–260).
