# Hypothesis Testing — the lesson

Course: Maths · Unit: Unit 16 — Further Statistics and Probability · Lesson: Hypothesis Testing
Built from: Pakistan, Statistics Class 12 (PCTB) — Jordan, Grade 12 Business Mathematics Term 2 — Libya, Grade 12 Foundations of Statistics (Science) — Kuwait, Grade 12 Term 1 (scientific track) — Laos, Grade 12

## Do it first
A coin is claimed to be fair. You toss it 10 times and get 9 heads. Fair coin having a lucky day — or a bent coin? You cannot KNOW. But you can decide, carefully, with the risk of being wrong stated in advance: if the coin were fair, 9 or 10 heads in 10 tosses happens with probability about 0.011 — rare enough that most judges would call the coin bent, accepting a small, known chance of condemning an honest coin. That is a hypothesis test: a claim, evidence shrunk to one number, a decision, and the price of error named before the evidence is seen. Pakistan's Statistics Class 12 book gives testing its longest chapter (Ch. 13, pp.111–180); this lesson runs it whole.

## Sub lesson 1 — Hypotheses, Tails and the Two Errors

**Hypotheses.** A **statistical hypothesis** is a claim about a population parameter. The **null hypothesis H₀** is the standing claim — no effect, no difference, the maker's word is true. The **alternative H₁** is what stands if H₀ falls. A hypothesis fixing one value is **simple**; one covering a range is **composite**. If H₁ says μ ≠ μ₀ the test is **two-tailed**; μ > μ₀ or μ < μ₀ make it **one-tailed**, right or left (Pakistan, Ch. 13, pp.111–114). Libya's Grade 12 Science book opens its testing chapter on the same pair — null and alternative hypotheses (Ch. 6, chapter start p.161) — and Jordan places hypothesis testing as the last lesson of its inference unit, after sample means and confidence intervals (Grade 12 Business, Unit 6, L4 p.141). Laos gives statistical hypothesis testing its own Grade 12 lesson (Ch. 5, L15, p.156).

**The two errors.** Deciding H₀ when it is true is right; the two ways to be wrong are: **Type I error** — rejecting H₀ when H₀ is TRUE (a false alarm), probability **α**, the level of significance, chosen by you in advance; **Type II error** — failing to reject H₀ when H₀ is FALSE (a missed catch), probability **β**. Pakistan defines both with the decision table (Ch. 13, pp.115–117); Libya teaches the errors a researcher can make in the same place (Ch. 6, p.161). α is yours to set — 0.05 is the common choice — and shrinking α widens the net for Type II: the two errors trade against each other on fixed evidence.

## Sub lesson 2 — The Procedure and Tests of a Mean

**The test statistic and the critical region.** The evidence is shrunk to one number, the **test statistic**, whose distribution under H₀ is known. The values too extreme for H₀ form the **rejection (critical) region**; its boundary values are the **critical values**; the rest is the acceptance region. The decision rule: statistic inside the critical region → reject H₀; outside → do not reject H₀. "Do not reject" is the honest phrase: the evidence did not convict H₀, which is not the same as proving it innocent.

**The nine steps.** Pakistan runs every test through one fixed procedure (Ch. 13, pp.115–117), in this shape: (1) state the claim in words; (2) set H₀; (3) set H₁, which fixes the tail or tails; (4) choose α; (5) choose the test statistic; (6) state its distribution under H₀; (7) fix the critical region; (8) compute the statistic from the sample; (9) decide. Nine steps, every time, in that order — the discipline is the point: the tails and α are fixed BEFORE the data speaks, so the data cannot move the goalposts.

**Tests about a mean.** With σ known, Z = (x̄ − μ₀)/(σ/√n) against standard normal critical values, for any n. With σ unknown and n small, t = (x̄ − μ₀)/(s/√n) with ν = n − 1. With n large, Z again, s standing in for σ. Pakistan works all three, including rejection values re-expressed for x̄ itself (Ch. 13, pp.120–130), and Libya's chapter likewise runs t-tests for a population mean (Ch. 6, p.161).

**Kuwait's way — two-sided only, and its recorded limits.** Kuwait's Grade 12 book teaches testing in its own strict shape (4-2, pp.177–181): H₁ is ALWAYS two-sided, H₁: μ ≠ μ₀; the statistic is chosen from its table — σ known → Z with any n; σ unknown, n ≥ 30 → Z with S; σ unknown, n < 30 → t = (x̄ − μ)/(S/√n) — and the decision is read off the acceptance region at 95%. Its worked cases: the salary claim H₀: μ = 4000 with n = 25, x̄ = 3950, σ = 125 gives Z = −2, outside (−1.96, 1.96) — reject H₀. A mean of 37.2 against μ = 37 (n = 80, S = 1.79) gives Z ≈ 0.999 — keep H₀. Food spending μ = 290 (n = 10, x̄ = 283, S = 32) gives t ≈ −0.6917 at df 9 against critical 2.262 — keep H₀. And its water-campaign pair teaches the deepest point in the lesson: the old study's Z = −1.66 keeps H₀, the new study's Z = −3.33 rejects it, because the new SPREAD shrank — the test measures distance in standard errors, not in raw units. Recorded negatives, part of the lesson: Kuwait's book contains **no p-values and no χ² tests**, and no tests for proportions — do not supply them under Kuwait's name.

Tip — from us, not from the books. Read every test statistic as one sentence: "how many standard errors is my sample from the claim?" Z = −2 says "two standard errors below the claim". If you can say that sentence, you can choose the table, the tails and the verdict without memorising cases.

## Sub lesson 3 — Proportions, Differences and Paired Tests

**Tests about proportions and differences.** A proportion is tested by the normal approximation, Z = (p − π₀)/√(π₀(1 − π₀)/n), with a count form and a continuity correction (Pakistan, Ch. 13, pp.135–139). Two independent means are tested by Z, by pooled t, or by large-sample Z (pp.142–151). Two proportions are tested with the proportion **pooled under H₀** — under the null the two populations share one π, so one pooled p builds the standard error (pp.169–174).

**The paired t test.** When the same units are measured twice — before and after — the pairs are the sample: form the differences d, and test their mean μ_D with t = d̄/(s_D/√n), ν = n − 1 (Pakistan, Ch. 13, pp.158–165). Pairing removes the person-to-person scatter from the evidence: a treatment that lifts EVERY pupil a little can be invisible between two group means and unmistakable in the differences. Using the two-sample machinery on paired data is the classic way to throw that power away.

**Who does NOT teach this — recorded negatives.** Four filings are explicit: the **Egypt**, **Cambodia**, **Greece** and **Iran** books teach no hypothesis testing — Egypt's statistics stops at confidence intervals, and Iran's book mentions Fisher once in a reading passage without ever teaching a test (Iran, Grade 11, p.79). None of the four is cited anywhere in this lesson. A country's not teaching a thing is evidence too, and the course records it as plainly as a teaching.

## Say it to your companion
Explain why the verdict is "reject H₀" or "do not reject H₀", never "H₀ is proved", using the courtroom shape: not guilty is not the same as innocent. Then trade: your companion explains how α and β trade against each other, and you explain why Kuwait's new water study rejected H₀ with a mean CLOSER to the target than the old study's.

## Do It Yourself
1. For the claim "this training raises scores", with the standing claim that it does nothing, write H₀ and H₁ (two-tailed), and name both errors in words. (Pakistan, Ch. 13, pp.111–117.)
2. Rebuild Kuwait's salary test from its givens — μ₀ = 4000, n = 25, x̄ = 3950, σ = 125 — and give Z and the verdict at 95%. (Kuwait, 4-2, pp.177–181.)
3. A sample of n = 16 from a normal population gives x̄ = 52, s = 8. Test H₀: μ = 50 two-tailed at α = 0.05 (t_{0.025,15} = 2.131). (Pakistan, Ch. 13, pp.120–130.)
4. In 200 tosses a coin lands heads 118 times. Test H₀: π = 0.5 two-tailed at α = 0.05 by the normal approximation. (Pakistan, Ch. 13, pp.135–139.)
5. Eight pupils score before: 40, 55, 48, 60, 52, 45, 58, 50 and after: 46, 58, 52, 63, 55, 50, 60, 54. Run the paired t test of "no change" at α = 0.05 (t_{0.025,7} = 2.365). (Pakistan, Ch. 13, pp.158–165.)
6. State, in one line each, why Kuwait cannot be cited for a p-value, and why Iran cannot be cited for any test at all.
