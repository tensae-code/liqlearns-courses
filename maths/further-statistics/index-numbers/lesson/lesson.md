# Index Numbers — the lesson

Course: Maths · Unit: Unit 16 — Further Statistics and Probability · Lesson: Index Numbers
Built from: Pakistan, Statistics Class 11 — Libya, Grade 12 Statistics (Humanities) — Iran, Mathematics and Statistics (2), Grade 11 — Iran, Statistics and Probability, Grade 11

## Do it first
Price one small basket twice. Take bread, milk and soap. In a year you choose as your base, say their prices were 20, 30 and 50. Now they are 25, 36 and 60. Try, before any formula, to answer in *one number*: "prices rose by ___." Each item rose by a different share — 25%, 20%, 20% — so one honest number has to combine them. That combining is this lesson: the index number.

## Sub lesson 1 — Simple Indices, Relatives and Chain Indices

**What an index number is.** An **index number** measures the change in a group of related values between a **base period** (set to 100) and a current period. Pakistan's Statistics Class 11 book builds the topic in full (Ch. 5, pp.128–158): simple index numbers with base = 100; the types — price, quantity and value indices, simple and composite; the uses, including the CPI, WPI and SPI; and the **construction steps**: state the purpose, choose the items, choose the base year, choose the weights, with weights W = V₀/ΣV₀ built from base-year values, and choose the average. Libya's Grade 12 Humanities book starts from the same place — the definition and importance of index numbers, worked on Libyan price data, including a basket of goods whose cost rises about 80% between two years (Ch. 2, pp.33–58). An index is always a comparison, never a price: 125 means "125% of the base", a rise of 25%.

**The unweighted indices.** Two first methods ignore quantities entirely. The **simple aggregative index** adds the prices themselves: Σpₙ/Σp₀ × 100. On the opening basket: (25 + 36 + 60)/(20 + 30 + 50) × 100 = 121/100 × 100 = **121**. The **average of relatives** turns each price into a relative first — pₙ/p₀ × 100 — and then averages the relatives, by the **mean, the median or the geometric mean**, all three in Pakistan's chapter: (125 + 120 + 120)/3 ≈ **121.7** by the mean. The relatives method does not care what units the prices were in; the aggregative method does, which is its known weakness.

**Link relatives and chain indices.** A **link relative** compares each year only with the year just before it. Multiply successive link relatives (as decimals) and you build a **chain index** against a fixed base. Pakistan's worked Example 5.6 (p.140) carries a book error, taught corrected here: in its link-relative table, the **potato** link relatives were misprinted, copied from the onion column. The correct values are **111.1** for 1981 (30/27 × 100) and **100.0** for 1982 (30/30 × 100) — not the printed 112.5 and 105.6. The book's totals, means and chain indices are correct once those two cells are corrected, as filed.

## Sub lesson 2 — The Weighted Indices

**The weighted indices — whose basket?** Real baskets have quantities, and the four named indices differ by which quantities do the weighing (Pakistan, Ch. 5; Libya, Ch. 2 — the weighted price relative index and the weighted aggregative price index, with Laspeyres, Paasche, Marshall–Edgeworth and Fisher all named in Libya's chapter):

- **Laspeyres** weighs with the **base year's** quantities: L = Σpₙq₀/Σp₀q₀ × 100. It prices the *old* basket at new prices.
- **Paasche** weighs with the **current year's** quantities: P = Σpₙqₙ/Σp₀qₙ × 100. It prices the *new* basket both ways.
- **Fisher** is the compromise, the geometric mean of the two: F = √(L × P) — Pakistan writes it exactly so, Fisher √(L×P).
- **Marshall–Edgeworth** weighs with the **sum of both years'** quantities: ME = Σpₙ(q₀ + qₙ)/Σp₀(q₀ + qₙ) × 100 — neither year's basket, but the two added together (Libya, Ch. 2).

Pakistan's Example 5.7 (p.143) is the lesson's worked set — taught corrected, never as printed. Two of its p₀qₙ cells are misprinted (B prints 140, correct 9 × 20 = 180; D prints 80, correct 10 × 5 = 50), so **Σp₀qₙ = 480, not the printed 470**. With that correction: **Paasche = 110.4, not the printed 112.8**, and **Fisher = 114.5, not the printed 115.8**. (One more cell, B's p₀q₀, prints 105 where 9 × 15 = 135 — but the column total 425 is right, so **Laspeyres 118.8 stands unaffected**.) Check Fisher for yourself: √(118.8 × 110.4) ≈ √13116 ≈ 114.5. Notice the order the corrected set makes sense of: Laspeyres highest, Paasche lowest, Fisher between them — the usual pattern, because the base basket holds more of what has risen most.

## Sub lesson 3 — CPI, Purchasing Power, Changing the Base and Inflation

**The CPI, and purchasing power.** The **consumer price index** is the index a country publishes for the cost of living; Pakistan's chapter names the family — **CPI** (consumer), **WPI** (wholesale), **SPI** (sensitive) — and describes the CPI as computed by Pakistan's Federal Bureau of Statistics from **464 items in 12 groups**, by the **family budget method, ΣIW/ΣW**: each group's index I weighted by its share W of family spending. Inflation rates are read off the CPI's changes. And the chapter's sharpest definition: the **purchasing power of money = 1/CPI**. With the CPI at 1.25 (index 125), purchasing power is 1/1.25 = 0.80 — today's money buys 80% of what base-year money bought. Libya's chapter adds the standard (base) basket idea and **changing the base**: to rebase a series, divide every index by the index of the new base year and multiply by 100. A series reading 120, 150, 180 on the old base, rebased to the middle year, reads 80, 100, 120.

**Iran's way — the basket ratio, and inflation.** Iran's Grade 11 Humanities book teaches the price index *as* a basket ratio, Laspeyres-style, inside its statistical-indices lesson, next to the poverty line (pp.56–60). Its worked example: bread and meat, base prices 1000 and 50000 rials, current prices 1500 and 70000, quantities 200 and 80 kg. The index is (1500·200 + 70000·80)/(1000·200 + 50000·80) × 100 = 5,900,000/4,200,000 × 100 ≈ **140.5** — recomputed and correct, as filed. Iran then **defines inflation as the change of the index** (p.60). Iran's other Grade 11 book states the rate form in a reading box: inflation rate = (P₁ − P₀)/P₀ × 100 (Statistics and Probability, pp.89–90). Its worked example — red meat from 28 to 32 thousand tomans — is taught corrected: (32 − 28)/28 × 100 = 14.2857…% ≈ **14.3%**, not the book's printed exact "14%", which states a rounded value as an equality, as filed.

> **Tip — from us, not from the books:** when two index numbers disagree, do not ask which is "right" — ask whose basket each one used. Laspeyres answers "what would the old basket cost now?"; Paasche answers "what does today's basket cost, then and now?"; Fisher splits the difference. Most arguments about "the real inflation rate" are basket arguments wearing index clothes.

## Say it to your companion
Explain each index to your companion using only the basket question: "Laspeyres — base basket. Paasche — current basket. Marshall–Edgeworth — both baskets added. Fisher — the geometric mean of Laspeyres and Paasche." Your companion then gives you a CPI number, and you must say two whole sentences back: the purchasing power it implies, and the percentage rise it means. Finish with Iran's example from memory: "The basket index is about 140.5, so prices rose about 40.5%, not 140.5%."

## Do It Yourself
1. Prices of three items: base 10, 40, 50; current 12, 50, 55. Find the simple aggregative index and the average of relatives (mean). (Answer: aggregative 117/100 × 100 = 117; relatives 120, 125, 110, mean ≈ 118.3.)
2. An index table gives Laspeyres 118.8 and, taught corrected, Paasche 110.4 (Pakistan, Example 5.7, p.143, corrected). Find Fisher. (Answer: √(118.8 × 110.4) ≈ 114.5.)
3. A CPI stands at 200 against its base year. Find the purchasing power of money and say it in a sentence. (Answer: 1/2.00 = 0.50 — money buys half what it bought in the base year.)
4. Prices rise from 28 to 32. Compute the inflation rate exactly as a fraction, then as a percentage to one decimal. (Answer: 4/28 × 100 = 14.2857…% ≈ 14.3% — the corrected value, not 14%.)
