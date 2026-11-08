# Moments, Skewness and Kurtosis — the lesson

Course: Maths · Unit: Unit 16 — Further Statistics and Probability · Lesson: Moments, Skewness and Kurtosis
Built from: Pakistan, Statistics Class 11 (Ch. 4) — Kuwait, Grade 11 Statistics Term 2 (lesson 4-2) — Cambodia, Grade 11 Basic student book and teacher guide (guide evidence for the skewness value)

## Do it first
Draw three little piles of stones on paper. Pile one: stones bunched in the middle, falling away evenly on both sides. Pile two: most stones on the left, a long thin trail stretching right. Pile three: most stones on the right, a trail stretching left. No formulas yet — just answer: which pile leans right? Which is balanced? This lesson builds the machinery that answers those questions with numbers: the **moments**, and the two shape verdicts they carry, **skewness** and **kurtosis**. In this library the machinery has one full home — Pakistan's Statistics Class 11 book, Chapter 4 (pp.104–120) — and this lesson follows it, with Kuwait's and Cambodia's books beside it for skewness.

## Sub lesson 1 — Moments About the Mean, an Origin and Zero

**Moments about the mean.** Take every value's distance from the mean, raise the distances to a power r, and average. That average is the **r-th moment about the mean**, written m_r (Pakistan, Ch. 4, pp.104–120). The family starts familiar: **m₁ = 0** always, because the signed distances from the mean cancel — a free check on every calculation. **m₂ is the variance** — the second moment is the spread you met last lesson. m₃, the average cubed distance, keeps its sign, so it feels any lean; m₄, the average fourth power, is dominated by far values, so it feels the peak and the tails. Work the ladder on 1, 2, 3, 4, 5 (mean 3): the distances are −2, −1, 0, 1, 2, so m₁ = 0, m₂ = (4 + 1 + 0 + 1 + 4)/5 = **2**, m₃ = 0, and m₄ = (16 + 1 + 0 + 1 + 16)/5 = **6.8**.

**Moments about an origin, and about zero.** The same averaging can be done around any chosen point A instead of the mean — moments about an **arbitrary origin**, the book's working device when the mean is untidy — and around **zero**, where the "distances" are the raw values themselves: the r-th moment about zero is simply the average of xʳ (Pakistan, Ch. 4). Pakistan's chapter gives the conversions between the families, so a moment found cheaply about a handy origin can be carried back to the mean, where its meaning lives. Grouped data gets the same treatment with the class width h in the working.

**Sheppard's corrections.** Grouping blurs values to class marks, and the blur inflates the even moments a little. **Sheppard's corrections** take the blur back out; the one this lesson uses is the second-moment correction, **corrected m₂ = m₂ − h²/12**, where h is the class width (Pakistan, Ch. 4). A grouped m₂ of 50 from classes of width 10 corrects to 50 − 100/12 ≈ **41.67** — the grouping's phantom spread removed.

## Sub lesson 2 — Skewness by Eye, by Pearson and by Bowley

**Skewness — which way it leans.** A distribution is **skewed** when it is not symmetric. Kuwait's Grade 11 Statistics book teaches the judgement first by eye and by centre (lesson 4-2, pp.19–22 — student-book stock): in a symmetric curve, mode = median = mean at one point; large values drag the mean to the right, giving a **right (positive) skew** — its worked test marks (max 20, 30 students) draw a curve tailing right and call the skew positive; small values drag it left, a **left (negative) skew**. The same book reads skewness off the **box plot**: in its daily-deposits example (Q1 = 32, median 41.5, Q3 = 46), the median sits closer to Q3 than to Q1, so the skew is to the left (p.21).

**Pearson's and Bowley's coefficients.** Pakistan's chapter turns the eye's judgement into numbers (Ch. 4). **Pearson's first coefficient** is (Mean − Mode)/S and his **second** is 3(Mean − Median)/S, with S the standard deviation — both ask how far the centres have been pulled apart, in spread units. **Bowley's coefficient** uses only the quartiles: (Q3 + Q1 − 2·Median)/(Q3 − Q1), always between −1 and 1. On Kuwait's deposits it gives (46 + 32 − 83)/(46 − 32) = −5/14 ≈ **−0.36** — negative, agreeing with the box plot. Cambodia's evidence enters here as **teacher evidence**: its Grade 11 Basic *guide* (printed p.236) answers a skewness item with (mean − mode)/SD = (22.04 − 22.5)/9.33 ≈ **−0.05** — a whisper of left skew, cited as the guide's answer, not as a student-book worked example.

## Sub lesson 3 — Moment Skewness and Kurtosis

**Moment skewness.** The third moment gives Pakistan's moment measures: **β₁ = m₃²/m₂³**, reported through **√β₁** (whose sign is the sign of m₃) and **b₁ = m₃²/m₂³** (Pakistan, Ch. 4). For the 1–5 ladder above, m₃ = 0, so √β₁ = 0 — no lean, exactly as the symmetric ladder promises. A distribution like 1, 2, 3, 4, 10 (mean 4, m₃ = 36, m₂ = 10) gives √β₁ = 36/10^1.5 ≈ **1.14** — a strong right lean in one number.

**Kurtosis — how peaked.** The fourth moment, standardised, is **β₂ = m₄/m₂²** (Pakistan, Ch. 4), and it judges the peak against the normal bell's value of 3: **β₂ = 3 is mesokurtic** (the middle, bell-like case), **β₂ > 3 is leptokurtic** (sharper peak, heavier tails), **β₂ < 3 is platykurtic** (flatter). The 1–5 ladder gives β₂ = 6.8/2² = **1.7** — platykurtic, and rightly: five evenly spaced values are as flat as data gets. Pakistan's chapter adds a percentile coefficient of kurtosis, K, beside β₂. Two of the book's own slips are taught corrected wherever this ground is used: in Example 4.7, Q1 is computed as **40.51** and then used, by a digit transposition, as 40.15 — the book's own final answers (semi-interquartile range 9.255, coefficient 0.19) agree with **40.51**, and 40.51 is the value here (p.91, corrected); and formula (4.22) prints the coefficient of quartile deviation as (Q3 − Q1)/(Q3 − Q1) — the denominator is **(Q3 + Q1)**, as the book itself uses on pp.89–91 (p.102, corrected).

> **Tip — from us, not from the books:** name the shape three times before you trust it — once by eye (follow the tail), once by centres (which of mean, median, mode has been dragged), and once by number (Pearson, Bowley or √β₁). When all three agree, the verdict is solid; when they quarrel, the quarrel itself is worth reporting, because real data leans differently at its middle and at its edges.

## Say it to your companion
Describe a distribution without drawing it: "It leans right — its mean sits past its median, its Bowley coefficient is positive, and its β₂ is under 3, so it is flat as well as leaning." Your companion sketches what they heard, then computes one check from numbers you give. Swap, and finish by saying the three kurtosis names with their β₂ bands from memory.

## Do It Yourself
1. For 1, 2, 3, 4, 5: recompute m₁, m₂, m₃, m₄ about the mean and confirm β₂ = 1.7. Name the kurtosis.
2. A grouped table gives m₂ = 50 with class width h = 10. Apply Sheppard's correction and state the corrected variance (≈ 41.67).
3. Using Q1 = 40.51 (corrected) with semi-interquartile range 9.255: recover Q3 (= 59.02), then compute the coefficient of quartile deviation with the corrected denominator (Q3 + Q1) and confirm ≈ 0.19.
4. A guide — teacher evidence — reports (22.04 − 22.5)/9.33 ≈ −0.05 for a set's skewness. Say what the sign and size claim, and say why this lesson files the value as teacher evidence, naming Cambodia's guide (p.236).
