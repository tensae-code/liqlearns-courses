# Monte Carlo and Simulation — the lesson

Course: Maths · Unit: Unit 16 — Further Statistics and Probability · Lesson: Monte Carlo and Simulation
Built from: Pakistan, Statistics Class 11 (Ch. 7) — China, Mathematics Compulsory Volume 2, A edition (Ch. 10)

## Do it first
A question needs 200 coin tosses — say, how often three coins in a row all land heads across a long evening of trials. Your arm votes no, and your arm is right. But the *information* in 200 tosses is only this: a string of heads and tails with no favourites. Anything that produces such a string — fairly, tirelessly, and ready to be checked — can do the tossing for you. This lesson builds that stand-in three ways, all from the books: a printed table of random digits, a rule that cooks random-looking numbers from one seed, and the method that puts them to work, **Monte Carlo simulation**.

## Sub lesson 1 — Random Numbers and Digits

**Random numbers and random digits.** Pakistan's Statistics Class 11 book opens its random-variables chapter with the raw material (Ch. 7, pp.186–196): **random numbers** and **random digits** — digits 0–9 with no digit favoured and no pattern to exploit — used to *construct* random variables from experiments: each digit (or block of digits) stands for an outcome, under a rule fixed before the run begins. Roll them out fairly and a table of digits becomes coins, dice, or people sampled from a list, as often as you need, at paper speed.

## Sub lesson 2 — The Congruential Generator and PPS Ranges

**The linear congruential generator.** A table must be printed by someone; a rule can be run by anyone. Pakistan's book gives the standard cooking rule, the **linear congruential generator**: xₙ₊₁ = a·xₙ + b (mod m) — multiply by a, add b, and keep only the remainder on division by m, which wraps every value back into 0, …, m − 1 (Ch. 7). Its worked run is the check to carry: seed **5**, with a = 13, b = 0, m = 16, gives **1, 13, 9, 5** — verify each step: 5 × 13 = 65, and 65 leaves remainder 1 on division by 16; 13 × 13 = 169 → 9; 9 × 13 = 117 → 5. The seed has returned, so the cycle repeats forever with period 4: these are *pseudo*-random numbers — random-looking, but one seed and one rule rebuild them exactly, which is their strength (anyone can check your run) and their warning (a short cycle is a poor factory).

**Table 7.1 at work.** Pakistan prints its random-number **Table 7.1** (p.189) and spends it on simulations: **coin tosses, two-coin and three-coin experiments**, the digits read off under a fixed correspondence and the simulated frequencies compared with the chances the theory promises (Ch. 7). The same chapter assigns random-number ranges **in proportion to size (PPS)**: from cumulative probabilities, each outcome is given a stretch of the number line as long as its probability — an outcome with probability 0.25 takes a quarter of the digits' range — so that one random number picks an outcome fairly, big chances getting big stretches.

## Sub lesson 3 — Monte Carlo and Testing a Model

**Monte Carlo.** Put the factory to work on a probability you cannot or will not compute directly: simulate the experiment very many times, count how often the event happens, and report the frequency as the estimate. That is the **Monte Carlo method**, named in Pakistan's chapter among the applications of its random numbers (Ch. 7). China's A-edition book teaches it as a named section — **random simulation / the Monte Carlo method** (§10.3.2, p.255) — inside its frequency-and-probability chapter, applied to problems of the shared-birthday and best-of-three kind: questions whose exact counting is thorny, but whose simulated frequency settles quickly. Lesson 129's moral governs the whole method: the estimate is a frequency, so it steadies only as the run lengthens — a Monte Carlo answer is always reported *with its run length*.

**Closing part — Mendel's peas: a model held up to counts.** China's chapter closes with a reading (pp.259–260 — a reading, as filed, and worded as one here) that turns the whole lesson outward: Gregor Mendel's pea crosses, recast as a **probability model**. A cross of two hybrid parents gives offspring **DD, Dd, dd** with probabilities **0.25, 0.5, 0.25**; since D dominates, the visible split is 0.75 dominant to 0.25 recessive — the famous **≈3:1 ratio** — and the reading holds the model's promises against the counts Mendel actually recorded. That is the scientific use of everything above: a model makes numerical promises; simulation tells you how much wobble to expect around them; real counts then judge the model. The model is not proved by one good match, and it is not hanged by one bad batch — it is *tested*, run by run, exactly as a Monte Carlo frequency is read.

> **Tip — from us, not from the books:** fix the dictionary before the run — which digits mean which outcomes, in which order you will read, and how many trials you will run — and write it at the top of the page. Every honest simulation in the books does this first; every dishonest one is just a frequency chosen after the fact.

## Say it to your companion
Walk your companion through one simulated toss in whole sentences: "I read the digits in pairs, even is heads, odd is tails, so this pair makes heads–tails — one simulated two-coin toss." Then swap: your companion runs the congruential wheel from seed 5 aloud, step by step, and you check the remainders. Finish by stating the Monte Carlo bargain together: "More runs, steadier frequency — and we always say how many runs."

## Do It Yourself
1. Run the generator with seed 5, a = 13, b = 0, m = 16 for eight steps and write the full sequence (1, 13, 9, 5, 1, 13, 9, 5). Say in one sentence why it had to repeat.
2. An outcome-split has probabilities 0.5, 0.25, 0.25. Assign PPS ranges over the digits 00–99 (Pakistan, Ch. 7 style) and justify each stretch's length.
3. Using digits from any random table, simulate 40 single-coin tosses under a written rule, report the heads frequency *with its run length*, and say why a classmate's 40-toss frequency may fairly differ from yours.
4. From the Mendel reading (China, pp.259–260): in 400 offspring of two hybrid parents, how many DD, Dd and dd does the model promise (100, 200, 100), and what dominant-to-recessive split follows? Word your answer as a model's promise, as the reading is filed.
