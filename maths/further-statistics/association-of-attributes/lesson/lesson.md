# Association of Attributes — the lesson

Course: Maths · Stage: Stage 16 — Further Statistics and Probability · Lesson: Association of Attributes
Built from: Pakistan, Statistics Class 12 (the sole full source) — Greece, Elements of Probability and Statistics C' Lykeiou (W11) (contingency tables, descriptive only)

## Do it first
Think of 100 people. For each person you know two yes/no things: are they literate, and are they employed? You cannot average a yes. But you can count: 40 people are both literate and employed, 20 are literate and not employed, 10 are not literate and employed, and 30 are neither. Four counts, four boxes. Before any name is given, guess: if literacy and employment had *nothing* to do with each other, how many of the 100 would you expect in the both-box? Hold your guess. This lesson — built on one country's full treatment, Pakistan's Statistics Class 12, Ch. 15 (pp.215–240) — gives that guess a formula, the leaning of the table a measure, and the whole question a test.

## Then the explanation
**Attributes and dichotomy.** A measurement gives a number; an **attribute** gives a quality — present or absent, yes or no. Pakistan's chapter opens by classifying a population by attributes: call the attribute A (literate) and its absence α (not literate), a second attribute B (employed) and its absence β. Splitting by one attribute is a **dichotomy**; the counts carry their own notation: (A) is the number with A, (AB) the number with both A and B, and so on. Two distinctions run the whole chapter. A **class frequency** like (A) counts everyone in a class, including those shared with other classes; the four boxes (AB), (Aβ), (αB), (αβ) are the **ultimate class frequencies** — the smallest boxes, where every person sits in exactly one. With k attributes there are 3^k class frequencies (each attribute: present, absent, or ignored) and 2^k ultimate ones. And a table must be **consistent**: no box negative, and every class frequency at least as large as any box inside it — a table that fails this is wrong before any test touches it (Ch. 15, pp.215–216).

**The 2×2 table.** Lay the four ultimate frequencies in a square:

|  | B | β | total |
|---|---|---|---|
| **A** | (AB) = 40 | (Aβ) = 20 | (A) = 60 |
| **α** | (αB) = 10 | (αβ) = 30 | (α) = 40 |
| **total** | (B) = 50 | (β) = 50 | n = 100 |

The margins are the class frequencies; the boxes are the ultimate ones; everything in this lesson is arithmetic on these nine numbers.

**The independence criterion.** If A and B have nothing to do with each other, the share of B-holders should be the same inside A as in the whole population: (AB)/(A) = (B)/n, which rearranges to the chapter's exact test: **(AB) = (A)(B)/n**. For our table the independence number is 60 × 50/100 = **30** — but the real (AB) is 40. The both-box holds ten more people than independence predicts, so the attributes lean together (Ch. 15, pp.217–219).

**Positive, negative and complete association — and Yule's Q.** Pakistan names the three cases (pp.219–220): **positive association** when (AB) > (A)(B)/n, as here; **negative association** when (AB) falls below it; **complete association** when one box empties the table's opposition — everyone with A also has B, or no one with A has B. The size of the leaning is **Yule's coefficient of association**:

Q = ((AB)(αβ) − (Aβ)(αB)) / ((AB)(αβ) + (Aβ)(αB))

For our table: Q = (40×30 − 20×10)/(40×30 + 20×10) = 1000/1400 ≈ **0.71** — a strong positive association. Q lives in [−1, 1]: Q = 1 or −1 is complete association, and Q = 0 is exactly independence. Note what Q uses: only the four boxes, never the margins directly — it measures the table's internal lean.

**Contingency tables.** Two attributes with more than two classes each — education level against income band, say — make an **r×c contingency table**: r rows, c columns, a count in every cell (Ch. 15, p.223). Greece's C' Lykeiou book teaches the same laying-out descriptively: contingency tables and bar charts (W11, Unit 2.5, pp.88–105), and comparing a quantitative characteristic across the categories of a qualitative one (Unit 2.6, pp.106–119). Greece's treatment stops there — descriptive only, no test, no Q, as filed — which is why the machinery that follows rests on Pakistan alone.

**The chi-square test of independence.** Q measures a 2×2 lean; the **chi-square test** judges any contingency table. Under the claim "the attributes are independent", each cell has an **expected frequency** e_ij = (row total × column total)/n — the independence criterion grown to fill the table. The statistic adds the standardised quarrel over all cells:

χ² = ΣΣ (o − e)²/e,  with degrees of freedom df = (r − 1)(c − 1),

compared against the χ² table at the chosen level (Pakistan prints its χ² quantiles in its Table 11, pp.298–299; χ²₁ at the 5% level is 3.84). For our table the expected twin is 30, 30, 20, 20, so χ² = 100/30 + 100/30 + 100/20 + 100/20 ≈ **16.67** on df = 1 — far beyond 3.84, so independence is rejected: the association is real, not a counting accident (Ch. 15, pp.224–232). Two guards stand on the test. First, the **expected-frequency rule**: every e should be at least 5; where a cell falls short, **pool** it with a neighbour row or column before computing — a χ² built on tiny expectations cannot be trusted. Second, **Yates' correction**, for 2×2 tables only: with df = 1 the smooth χ² curve fits the jumpy counts worst, so shrink each |o − e| by 0.5 before squaring. Corrected, our table gives χ² ≈ (9.5²/30) + (9.5²/30) + (9.5²/20) + (9.5²/20) ≈ **15.04** — smaller, as a correction should make it, and the decision is unchanged.

**The contingency coefficient.** A test answers yes or no; it does not size the association in a big table the way Q sizes a 2×2. Pakistan's **coefficient of contingency** does: **C = √(χ²/(n + χ²))** (Ch. 15, p.226, within the chapter's test run pp.224–232). For our table, C = √(16.67/116.67) ≈ **0.378**. C is never negative and never reaches 1 — its ceiling depends on the table's size — so it compares tables of the same shape, not across shapes. (The chapter also names φ² = χ²/n, the mean-square contingency from which C is built.)

**The recorded boundary.** Say it plainly, because the lesson's honesty is part of its content: **Pakistan's book teaches no chi-square goodness-of-fit test.** Its χ² appears only as a test of independence in Ch. 15; the filing records the goodness-of-fit test, any test about a variance, and any F-test as absent from the book. So this lesson contains no goodness-of-fit part, and no source in it may be quoted for one. What the chapter does teach, it teaches complete: attributes, the criterion, Q, the test with its two guards, and C.

> **Tip — from us, not from the books:** before computing anything, write the expected table next to the real one and just look at the two. The cell where they quarrel most is usually the whole story of the table — the test only confirms, with a number, what that side-by-side look already shows.

## Say it to your companion
Take a fresh pair of qualities — trained or not, passed or not — and make your companion name all four boxes in the (A)/(α)/(B)/(β) language and say who sits in each. Then give them a Q value, say Q = −0.8, and make them say it whole: "a strong negative association — the attributes lean apart, near to complete." Finish by reciting the two guards from memory: expected frequencies of at least 5, pooling where they fall short; and Yates' half-unit correction in every 2×2 table.

## Do It Yourself
1. A survey of 100 people gives: (A) = 60, (α) = 40, (B) = 50, (β) = 50, (AB) = 40, (Aβ) = 20, (αB) = 10, (αβ) = 30 (the lesson's table, Pakistan Ch. 15 shape). Check consistency, then compute the independence number (A)(B)/n and say which way the association leans. (Answer: consistent; 30; the real 40 is above it — positive.)
2. For the same table, compute Yule's Q in full and interpret it. (Answer: Q = 1000/1400 ≈ 0.71, strong positive.)
3. Build the expected table, run χ² with df, and decide independence at the 5% level (χ²₁ = 3.84). Then repeat with Yates' correction. (Answers: χ² ≈ 16.67, reject independence; corrected χ² ≈ 15.04, same decision.)
4. Compute the contingency coefficient C for the table, and finish by writing one sentence stating what test this book does **not** teach. (Answer: C ≈ 0.378; the book teaches no chi-square goodness-of-fit test — χ² is used only for independence.)
