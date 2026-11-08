# Estimation and Confidence Intervals — the lesson

Course: Maths · Unit: Unit 16 — Further Statistics and Probability · Lesson: Estimation and Confidence Intervals
Built from: Pakistan, Statistics Class 12 (PCTB) — Jordan, Grade 12 Business Mathematics Term 2 — Kuwait, Grade 12 Term 1 (scientific track) — Egypt, Statistics Grade 12 — Libya, Grade 12 Foundations of Statistics (Science) — Laos, Grade 12 — Iran, Grade 11 Statistics and Probability (Mathematical Sciences) — China, Mathematics Compulsory Volume 2, A edition (reading)

## Do it first
A jar holds sweets. You may shake it and look, but not open it. First: give ONE number for how many sweets are inside. Then: give a RANGE — "between … and …" — that you would bet a coin on. The single number is sharper; the range is more honest. Estimation is the craft of making both, and of knowing how wide the range must be before the bet is fair. Pakistan's Statistics Class 12 book opens its estimation chapter on exactly this split — statistical inference, point against interval estimation, estimator and estimate (Ch. 12, p.73).

## Sub lesson 1 — Point Estimation and Unbiasedness

**Point estimation, interval estimation.** An **estimator** is the rule (the statistic); an **estimate** is the number it gives on your sample. A **point estimate** is one number: x̄ for μ, p for π. An **interval estimate** is a range built around the point estimate, with a stated confidence. Laos's Grade 12 book gives estimation its own lesson (Ch. 5, L14, p.145), Libya's Science book teaches the same two types and then the confidence interval for a population mean (Ch. 5, pp.144–147), and Egypt's Statistics book closes its normal-distribution unit with estimation and confidence intervals (Unit 5, 5-3, p.136). Jordan builds the road in order: the distribution of sample means first, then confidence intervals inside its inference unit (Grade 12 Business, Unit 6, L1 p.102; L3 p.128).

**Unbiasedness.** An estimator is **unbiased** when its sampling distribution centres exactly on the parameter: E(T) = θ. Pakistan proves the famous case by enumeration (Ch. 12, pp.74–76): the sample variance computed with denominator n, S², averages to ((n − 1)/n)σ² — biased low — while Ŝ², with denominator n − 1, averages to σ² exactly. That is why the n − 1 divisor exists. Among unbiased estimators, the best is the one with the smallest variance; Pakistan also pools information across samples — pooled mean, pooled variance, pooled proportion (pp.76–79).

**The point estimation error is NOT the standard error.** Kuwait's Grade 12 book, in its margin-of-error section, prints that the absolute difference |x̄ − μ| "is called the standard error and equals σ/√n" (4-1, p.171). Taught corrected, never as printed: **|x̄ − μ| is the point estimation ERROR** — the one realised miss of your one sample, which you usually cannot even know, since μ is unknown. The **standard error** is σ/√n — a property of the METHOD, the spread of x̄ over all possible samples. Kuwait's own next paragraph uses σ/√n correctly inside the margin of error, E = z_{α/2}·σ/√n; only the label on p.171 is wrong, and this lesson teaches the corrected label.

Tip — from us, not from the books. Error is about YOUR sample; standard error is about EVERY sample. If a formula needs μ itself, it cannot be a tool you use — it can only be a definition of how far off you were. That test catches the p.171 slip at once.

## Sub lesson 2 — Confidence Intervals for a Mean

**Confidence intervals for a mean — σ known.** The interval is x̄ ± E, with margin of error E = z_{α/2}·σ/√n, and the **confidence level** 1 − α is the long-run catching rate of the method: 95% of intervals built this way catch μ. Kuwait works its pulse-rate study in full: n = 40, σ = 12.5, x̄ = 76.3 gives E ≈ 3.8738 and the 95% interval (72.4262, 80.1738) (4-1, pp.168–176). Pakistan teaches the same z interval, its interpretation, the large-sample form justified by the Central Limit Theorem, and the finite-population-correction form for sampling without replacement (Ch. 12, pp.82–90). Note Kuwait's discipline: only the 95% level is used anywhere in that book.

**Confidence intervals for a mean — σ unknown.** With σ unknown and a small sample, s replaces σ and the t distribution replaces z, with ν = n − 1 degrees of freedom. Kuwait works it: n = 25, S = 10, x̄ = 15, t_{0.025} = 2.064 at df 24, so E = 4.128 and the interval is (10.872, 19.128) (4-1, pp.168–176). For large samples the z form with s in place of σ is used instead — Kuwait's n = 36, x̄ = 60, s = 4 case gives E ≈ 1.3067 and (58.6933, 61.3067). Pakistan teaches the t interval the same way (Ch. 12, pp.82–90). The t interval is wider: you pay for not knowing σ.

## Sub lesson 3 — Proportions, Differences and the German Tank Problem

**Intervals for a proportion, and for differences.** A proportion gets p ± z·√(p(1 − p)/n), with and without replacement (Pakistan, Ch. 12, pp.92–95). Comparing two populations, Pakistan first separates independent samples from paired samples (p.96), then builds intervals for μ₁ − μ₂ — known variances, large samples, and the pooled-variance t interval with ν = n₁ + n₂ − 2 (pp.96–103) — and for π₁ − π₂ (pp.105–107). Every interval in this lesson has the same skeleton: estimate ± (table value) × (standard error of that estimate). Learn the skeleton once; the parts change, the shape does not.

**Iran's way — estimation without the machinery.** Iran's Grade 11 Statistics and Probability book (Mathematical Sciences) teaches inference in its own shape: data collection, census against sampling and sources of bias first (Ch. 4, pp.98–111), then point estimation of a mean and a proportion from a sample, and interval estimation introduced with the picture of the sample-mean distribution (pp.112–121) — with NO z-values table and no named confidence-level machinery. The idea is the same; the apparatus is deliberately lighter. Record the boundary plainly: that book does not teach hypothesis testing at all — the term appears once, as a historical mention of Fisher in a reading passage (p.79) — so Iran is a source for estimation here and is cited nowhere in the hypothesis-testing lesson.

**Closing part — the German tank problem.** China's A-edition book carries a reading on a wartime estimation triumph (Ch. 9, reading, pp.208–209): captured German tank parts carried serial numbers. If the parts are a random sample from a run numbered 1 to N, the largest serial seen, x_max, underestimates N — but by a repairable amount: the estimate is **N ≈ x_max·(n + 1)/n**, where n is the number of parts seen. Five parts, largest serial 48: N ≈ 48 × 6/5 = 57.6, about 58 tanks. No distribution, no interval — one order statistic and one correction factor, and historically it beat the intelligence estimates. It is the purest point estimate in the course: a single number, honestly derived.

## Say it to your companion
Explain why "there is a 95% probability that μ lies in (72.43, 80.17)" is the wrong sentence, and say the right one: the METHOD catches μ in 95% of its intervals; this interval either caught it or it did not. Then trade: your companion explains why Ŝ² divides by n − 1, and you explain why |x̄ − μ| cannot be the standard error — using the test "could you compute it without knowing μ?"

## Do It Yourself
1. A sample of n = 49 has x̄ = 30 and σ = 7 (known). Build the 95% interval for μ. (Pakistan, Ch. 12, pp.82–90.)
2. Rebuild Kuwait's t interval from its givens — n = 25, S = 10, x̄ = 15, t_{0.025} = 2.064 — and check you land on (10.872, 19.128). (Kuwait, 4-1, pp.168–176.)
3. A sample of 400 voters has 236 for a candidate. Build the 95% interval for π. (Pakistan, Ch. 12, pp.92–95.)
4. Two independent samples: n₁ = n₂ = 30, x̄₁ = 52, x̄₂ = 47, pooled s = 10. Build the 95% t interval for μ₁ − μ₂ with ν = 58 (use t ≈ 2.00). (Pakistan, Ch. 12, pp.96–103.)
5. Four captured parts carry serials 7, 19, 31, 44. Estimate the production run by the German tank rule. (China, reading, pp.208–209.)
6. In one sentence each: what does Iran's book give the learner for estimation, and what does it deliberately leave out? (Iran, Ch. 4, pp.112–121.)
