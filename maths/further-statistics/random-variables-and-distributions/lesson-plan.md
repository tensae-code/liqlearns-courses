# Lesson plan — Random Variables and Distributions

**Course:** Maths · **Stage:** Stage 16 — Further Statistics and Probability · **Lesson:** Random Variables and Distributions
**Place in the curriculum:** Level 118 of 136, the second lesson of Stage 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** a random variable — a number tied to each outcome — and the named distributions that say how likely each of its values is: binomial, hypergeometric, Poisson, uniform and normal, with expectation, variance and the CDF.
**This lesson's own level:** it stands on Probability (Stage 11) and on Conditional Probability and Bayes' Theorem (Level 117, same stage) — events, chances that add to 1, and chances that change when the situation changes. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Before this lesson
- Recommended first: Probability (Stage 11) — a distribution is a probability list with a number attached to each outcome. Recommended, never forced.
- Recommended first: Conditional Probability and Bayes' Theorem (Level 117, same stage) — sampling without replacement, which the hypergeometric distribution counts, is dependent-draw ground. Recommended, never forced.
- Recommended first: Averages and Spread (Stage 11) — expectation is a mean, variance is a spread. Recommended, never forced.

## What the learner can do when it ends
1. Say what a random variable is, and split variables into discrete and continuous (Indonesia's Grade 12 TL Revisi book, Definisi 4.1, p.227; discrete p.232, continuous p.239; Pakistan's Statistics Class 11, Ch. 7, pp.193–194).
2. Write a probability mass function table, check it sums to 1, and never accept a table that sums to more — Pakistan's p.206 example is taught corrected: its seven probabilities sum to 1.07, not 1, so as printed it is not a valid distribution (Pakistan Statistics Class 11, Ch. 8, p.206, corrected).
3. Find expectation E(X) and variance Var(X) from a table (Kuwait's Grade 12 Statistics book, Unit 4, pp.14–37; Egypt's Statistics book, Unit 4, pp.93–115).
4. Use the cumulative distribution function F(x) = P(X ≤ x), with the discrete interval forms taught corrected — Kuwait's p.169 summary forms are false for discrete variables and are taught in their corrected forms (Kuwait Grade 12 Term 2, Unit 8, pp.140–177, summary p.169 corrected as filed).
5. Work the binomial distribution: P(X = x) = C(n,x) pˣ qⁿ⁻ˣ, E(X) = np, Var(X) = npq — with Indonesia's coefficient taught corrected as (n/x), not (n/p) (Indonesia TL Revisi, Definisi 4.6, p.256, corrected).
6. Tell the named distributions apart and pick the right one: hypergeometric for sampling without replacement (Pakistan Statistics Class 11, Ch. 9, pp.233–249, with p.245 taught corrected: P(X = 5) = 0.003968 and 5 tomato cans, not 7), Poisson (Libya Grade 12, Ch. 3), uniform (Indonesia's 2022 TL book only — the uniform distribution is not in the Revisi book), geometric (Egypt Statistics, Unit 4, p.100), and normal.
7. Standardise with a z-score, z = (x − μ)/σ, read the normal table, and use the empirical rule 68–95–99.7 as a named part (Kuwait Grade 11 Statistics, lesson 4-3, pp.27–32; the Kuwait Grade 11 Term 1 workbook rows at pp.93–96 are workbook evidence only — the student book is not in hand).

## What you need
Paper and a pencil.
A coin and a die.
A normal (z) table — the books print their own (Indonesia TL Revisi, appendix pp.281–282; Cambodia Grade 11 Basic, p.246; Laos Grade 12, appendix p.293).

## The run of the lesson (in order)
1. **Do it first** — the learner tosses two coins, writes the number of heads each time, and builds the count table before any name is given (lesson/lesson.md).
2. **The explanation** — random variables, discrete and continuous; pmf and pdf; expectation and variance; the CDF; then the named distributions one by one — binomial, hypergeometric, Poisson, uniform, geometric, normal — closing with z-scores and the empirical rule as a named part (lesson/lesson.md).
   - ADD IMAGE at the pmf part: a picture of a probability table drawn as bars on sticks, the bar heights adding to one whole — the student checks the heights sum to 1.
   - ADD GIF at the CDF part: a picture of a staircase climbing as x grows, each step the height of one value's probability — the student reads F(4) off the stair it lands on.
   - ADD IMAGE at the normal part: a picture of a bell curve split into the 68–95–99.7 bands — the student points at the band between μ − σ and μ + σ and says its share.
   - ADD GIF at the binomial part: a picture of the binomial bars for 10 trials sliding as p moves from small to one half — the student watches the tallest bar move.
3. **Say it to your companion** — name a variable, say whether it is discrete or continuous, and name the distribution that fits a story your companion tells (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — random variables and the named distributions in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — a full table worked for E and Var, one binomial, one hypergeometric and one z-score calculation (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a pmf drawn as bars on sticks summing to 1 → the student checks the sum.
- GIF — a picture of a CDF staircase climbing value by value → the student reads a value off the stair.
- IMAGE — a picture of a bell curve split into the 68–95–99.7 bands → the student names each band's share.
- GIF — a picture of binomial bars sliding as p changes → the student watches the tallest bar move.
- VIDEO — the video-script filmed (made later) → the student builds the two-coin table along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Accepts a pmf table without checking → always add the probabilities first. Pakistan's own p.206 example sums to 1.07 as printed and is taught corrected here: a table that does not sum to 1 is not a distribution, whoever printed it.
- Confuses pmf and pdf → a discrete variable has *probabilities at points* (they sum to 1); a continuous variable has a *density curve* (areas are probabilities, the total area is 1, and the probability of one exact value is 0). Indonesia's Revisi book keeps the two in separate places for a reason: probability function p.242, density function p.249.
- Uses the binomial for a without-replacement draw → no replacement means the chances change, so the count is hypergeometric, not binomial. Pakistan teaches the two in the same chapter (Ch. 9) so the contrast is visible.
- Reads a Kuwait CDF interval straight off the p.169 summary → that summary is false for discrete variables; use the corrected forms in the lesson (for discrete X, P(a ≤ X ≤ b) = F(b) − F(a) + P(X = a)).
- Looks for the uniform distribution in Indonesia's Revisi book → it is not there; the uniform distribution in this lesson rests on the 2022 TL book (Bab 5, pp.169–196) and on Kuwait and Pakistan.
- This lesson's next door: Sampling and Sampling Distributions (Level 119, same stage) — what happens to a mean when the experiment is a whole sample.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Classes 11 and 12 — with its p.206 and p.245 errors taught corrected, and its appendix tables at printed pp.301–306 cited nowhere; Indonesia Grade 12 TL 2022 and TL Revisi 2025 — with Definisi 4.6 taught corrected, and the uniform distribution resting on the 2022 book only; Kuwait Grade 12 Term 2, Grade 12 Statistics Term 2, Grade 11 Statistics Term 2 and the Grade 11 Term 1 workbook — workbook evidence only for the z-score rows, the student book not being in hand, and its p.169 CDF summary and p.171 binomial table taught corrected; Egypt Statistics Grade 12; Jordan Grades 11 and 12 and Grade 12 Business; Libya Grade 12 Foundations of Statistics — its Grade 11 Statistics books teach no distributions and are cited nowhere here; Vietnam's Grade 12 study book — discrete variables and binomial only, no continuous distributions anywhere in Vietnam, as filed; Yemen Grade 12 Science; Armenia Grade 10 and its Grade 12 guide as teacher evidence; Cambodia Grade 12 Advanced, Grade 11 Basic and the PRIVATE Probability booklet; Laos Grades 11 and 12; Iran Grade 10 — a descriptive bell curve only, whose "96 of 100" wording is loose, not exact, and never cited as an exact figure). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
