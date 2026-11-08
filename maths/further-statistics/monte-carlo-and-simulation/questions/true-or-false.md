# Monte Carlo and Simulation — true or false

Sub-lesson markers (2026-11-08 restructure): every item's marker names the sub lesson it belongs to. The files' old depth groups map onto the sub lessons as: (Level 1) -> Sub lesson 1 — Random Numbers and Digits · (Level 2) -> Sub lesson 2 — The Congruential Generator and PPS Ranges · (Level 3) -> Sub lesson 3 — Monte Carlo and Testing a Model.

Say true or false. If it is false, say why.

**1. (Sub lesson 1)** A simulation's digit rule may be changed mid-run if the results look odd.
**Answer:** False — the rule is fixed before the run; changing it mid-run rigs the experiment (Pakistan, Ch. 7).

**2. (Sub lesson 1)** Table 7.1 is a table of logarithms.
**Answer:** False — it is Pakistan's printed random-number table (p.189).

**3. (Sub lesson 2)** From seed 5, the generator with a = 13, b = 0, m = 16 never returns to 5.
**Answer:** False — it returns in four steps: 1, 13, 9, 5 — and then repeats.

**4. (Sub lesson 2)** Under PPS, a more probable outcome receives a longer stretch of random numbers.
**Answer:** True — ranges are assigned from cumulative probabilities, in proportion to size (Pakistan, Ch. 7).

**5. (Sub lesson 3)** One simulated run of 10 trials settles a probability as well as a run of 10,000.
**Answer:** False — a Monte Carlo estimate is a frequency; short runs wobble, long runs steady (China, §10.3.2, p.255).

**6. (Sub lesson 3)** The Mendel part of this lesson is a theorem proved in China's student book.
**Answer:** False — it is filed as a reading (pp.259–260) and is worded as one: a model tested against counts.
