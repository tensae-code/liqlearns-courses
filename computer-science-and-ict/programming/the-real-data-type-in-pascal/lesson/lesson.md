# The Real Data Type in Pascal

## Do it first

Not everything counted is whole. Measurements, money with fractions, averages — Grade 7's next Pascal type is the number line itself: real.

## Sub lesson 1 — Real — numbers with a fractional part

The **real** type holds numbers **with fractional parts**: 3.14, −0.5, the average 7.333…. A real value may be written in **fixed form** (2.75) or in **exponent form** (2.75E3 = 2750), the form science uses for the very large and very small. Declaration mirrors integer's: `var x: real;`. Unlike an integer's exact shelf of values, a real is held **approximately** — the type stores a very close neighbour of the true value, a fact whose consequences the Grade 12 error lessons will cash in.

In your mind's eye: real — numbers with a fractional part.

[Picture 47868 — real — numbers with a fractional part]

## Sub lesson 2 — Operations on reals — smooth arithmetic, careful equality

Reals take the full arithmetic: +, −, *, and **/** — division that keeps the fraction (7 / 2 = 3.5, where integer div gave 3). The standard functions serve them: **abs**, **sqr**, **sqrt**, **sin**, **cos** and their kin take reals and answer reals. One warning travels with the type: because reals are approximate, **testing two reals for exact equality is unsafe** — 0.1 + 0.2 may not sit exactly on 0.3. Compare reals by closeness, not by identity: the professional's habit, taught from the first real lesson.

In your mind's eye: operations on reals — smooth arithmetic, careful equality.

[Picture 47869 — operations on reals — smooth arithmetic, careful equality]

## Say it to your companion

Tell your companion, in your own words: The **real** type holds numbers **with fractional parts**: 3.14, −0.5, the average 7.333…. A real value may be written in **fixed form** (2.75) or in **exponent form** (2.75E3 = 2750), the form science uses for the very large and very small. Declaration mirrors integer's: `var x: real;`. Unlike an integer's exact shelf of values, a real is held **approximately** — the type stores a very close neighbour of the true value, a fact whose consequences the Grade 12 error lessons will cash in. Reals take the full arithmetic: +, −, *, and **/** — division that keeps the fraction (7 / 2 = 3.5, where integer div gave 3). The standard functions serve them: **abs**, **sqr**, **sqrt**, **sin**, **cos** and their kin take reals and answer reals. One warning travels with the type: because reals are approximate, **testing two reals for exact equality is unsafe** — 0.1 + 0.2 may not sit exactly on 0.3. Compare reals by closeness, not by identity: the professional's habit, taught from the first real lesson. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Numbers with fractional parts — measurements, fractions, averages. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Fixed form (2.75) and exponent form (2.75E3 = 2750). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: var x: real;. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — approximately; the type stores a very close neighbour of the true value. Do this with a real example of your own and write or say how you know it is right.
