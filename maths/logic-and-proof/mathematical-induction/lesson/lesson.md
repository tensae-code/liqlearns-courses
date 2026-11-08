# Mathematical Induction — the lesson

Course: Maths · Unit: Unit 13 — Logic and Proof · Lesson: Mathematical Induction
Built from: Pakistan, Mathematics Class 11 — Armenia, Algebra and Analysis 11 (natural-mathematics and general streams) — Vietnam, Grade 10 study book (Chuyên đề học tập Toán 10) — Greece, Grade 11 orientation book (W7) — Cambodia, Grade 11 Advanced — Kazakhstan, Grade 9 Algebra books (Yelemessov; Shynybekov; Abylkasymova; Soltan) — Laos, Grade 11 — Iraq, Grade 12 Scientific (filed "for information only")

## Do it first
Compute n² − n + 41 for n = 1, 2, 3, 4. You get 41, 43, 47, 53 — all prime. Try n = 5, 6, 10: 61, 71, 101 — prime again. Is the claim "n² − n + 41 is prime for every natural n" proved now? Pakistan's Class 11 book opens its induction unit with this very polynomial — Euler's — as the warning exhibit before the method: the claim survives forty checks and dies at the forty-first (Unit 8, pp.140–150; the failure itself is computed below). Checking is not proving. This lesson is the machine that proves such claims — or, like this one, shows exactly why no proof can exist.

## Then the explanation

## Sub lesson 1 — The Principle and the Three Steps

**The principle.** Let P(n) be a statement about the natural number n. If
1. P(1) is true, and
2. whenever P(k) is true, P(k + 1) is true,
then P(n) is true for every natural n. The picture is a row of dominoes: the first falls, and each one knocks down the next, so all fall. Laos's Grade 11 book states the principle for statements A(n) with the three steps named: n = 1; assume n = k; prove n = k + 1 (Ch.2 L7, p.28). Kazakhstan's Yelemessov Algebra 9 motivates it with the domino picture the same way (§3.1, p.80). Armenia teaches the method twice in Grade 11 — in the general stream inside its logic-and-sequences chapter (§4, p.51) and in the natural-mathematics stream with a further section of applications (§2, p.87; §3, p.94). Vietnam's Grade 10 study book calls it the first formal proof method of the series (Bài 3, p.25). Greece carries it in the number-theory chapter of its Grade 11 orientation book (W7, Ch.4, pp.135–184).

## Sub lesson 2 — Series and Divisibility Proofs

**A series proof in full.** Claim: 1 + 3 + 5 + … + (2n − 1) = n². This is the opening induction proof of Cambodia's Grade 11 Advanced book (Ch.1 L3, pp.24–34), and the same result is a worked proof in Kazakhstan's Soltan Algebra 9 (§14, p.100).
- **Base (n = 1):** the left side is 1; the right side is 1² = 1. True.
- **Hypothesis:** suppose 1 + 3 + … + (2k − 1) = k² for some k.
- **Step (k + 1):** 1 + 3 + … + (2k − 1) + (2k + 1) = k² + (2k + 1), using the hypothesis on the first part, and k² + 2k + 1 = (k + 1)². True for k + 1.
So the formula holds for all n. The companion formula 1 + 2 + … + n = n(n + 1)/2 is proved the same way in Kazakhstan's Yelemessov book (§3.1, p.80) and Abylkasymova book (§18, p.153).

**A divisibility proof.** Claim: 6²ⁿ − 1 is divisible by 35 for all n — a worked proof in Kazakhstan's Abylkasymova Algebra 9 (§18, p.153).
- **Base (n = 1):** 6² − 1 = 35, divisible by 35. True.
- **Hypothesis:** suppose 35 divides 6²ᵏ − 1, say 6²ᵏ − 1 = 35m.
- **Step:** 6²⁽ᵏ⁺¹⁾ − 1 = 36 · 6²ᵏ − 1 = 36(6²ᵏ − 1) + 35 = 36 · 35m + 35, divisible by 35. True for k + 1.
The standard move is visible: multiply out, split off the k-case, and let the hypothesis do the work. Pakistan's unit proves divisibility, integrality, series formulas and an inequality by the same pattern (Unit 8, pp.140–150); Cambodia's chapter continues into further proofs and applications, including work with the harmonic series 1 + 1/2 + … + 1/n (pp.24–34).

## Sub lesson 3 — Extended Induction, Inequalities and the Counter-Example Warning

**Inequalities and extended induction.** Induction also proves inequalities — Kazakhstan's books prove 2ⁿ > n² for n ≥ 5, which shows a first refinement: the staircase may start later than n = 1, provided the base case is the true starting point and the step works from there on (Soltan, §14, p.100; Shynybekov, §3.2*, p.72, proving Bernoulli's inequality 2ⁿ > n² for n > 5 there as filed). Pakistan names the wider tool **extended induction**: the hypothesis and step are set up so several earlier cases, or a later starting case, carry the next one (Unit 8, pp.140–150). Vietnam immediately puts the method to work: its next study lesson proves Newton's binomial theorem by induction (Bài 4, p.32) — and Pakistan's binomial theorem is likewise proved by induction in its own unit (Unit 8).

Tip — from us, not from the books. In the step, write the (k + 1) target down first and keep it in sight. Almost every stuck induction unsticks the moment you ask: "what must the k-case become, and what is the gap between them?" The gap is usually one term — 2k + 1 above — or one factor, like the 36 above.

**The counter-example warning — core content, not a footnote.** Euler's polynomial n² − n + 41 is prime for n = 1, 2, …, 40 — forty confirmations. At n = 41: 41² − 41 + 41 = 41² = 1681, composite. The claim is false, and no amount of further checking could have proved it true; only the induction machine proves "for all n", and here the machine cannot even start, because the step is simply false. Kazakhstan's Shynybekov book makes the mirror-image point from inside the method: its starred induction section dissects a deliberately false "proof" — the claim that n² + n + 41 is always prime fails at n = 41 in that book's form too — and states the principle formally, A(1) and A(k) ⇒ A(k + 1), so pupils see both guards at once (§3.2*, p.72). (Keep the two polynomials apart, as the books file them: Pakistan's is n² − n + 41; Kazakhstan's dissected claim uses n² + n + 41. Both fail at n = 41.) Soltan's book sets "find the student's error" items in its induction exercises, including a false induction proving 2k + 2019 = 2(k + 1) + 2019 (§14, p.100).

**One filed boundary.** Iraq's Grade 12 Scientific book proves De Moivre's theorem by induction at pp.42–43 — filed "for information only", and it is recorded here in exactly those terms: the filing carries the proof as information only, so this lesson names the fact and does not build on it.

## Say it to your companion
Talk your companion through the n² proof from memory, naming the three parts as they come — "base", "hypothesis", "step" — and at the step, say out loud exactly where the hypothesis is used. Then trade: your companion explains, with the tally of 40 primes, why Euler's polynomial shows that checking cases is not a proof, and names the n where it breaks.

## Do It Yourself
1. Prove by induction: 1 + 2 + … + n = n(n + 1)/2.
2. Prove by induction: 4ⁿ + 2 is divisible by 3 for all n (a Soltan exercise, §14, p.100 — the step adds a multiple of 4ⁿ⁺¹ − 4ⁿ; keep the hypothesis in sight).
3. Prove by induction: the number of diagonals of a convex n-gon is n(n − 3)/2 (filed among Abylkasymova's §18 exercises, p.153).
4. Compute n² + n + 41 at n = 41 and state, in one sentence, what it does to the claim "always prime."
5. State where your proof in task 1 would break if the base case were deleted — which later step secretly depends on it?
