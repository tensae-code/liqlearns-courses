# Hands-on — Taylor and Maclaurin Series

The lesson rebuilt functions as endless polynomials, the way Pakistan's Class 12 book does it (§2.17, ch-pp.74–81).

## e by hand
Add the Maclaurin terms of eˣ at x = 1 one at a time: 1; +1 = 2; +1/2 = 2.5; +1/6 ≈ 2.667; +1/24 ≈ 2.708; +1/120 ≈ 2.717. Write each running total. The sum is settling on e ≈ 2.718 — you can watch a series converge in six lines (Pakistan, Class 12, §2.17, ch-pp.74–78).

## How many terms does sin need?
Compute sin(0.5) (radians) three ways: x alone (0.5); x − x³/6 (≈ 0.4792); x − x³/6 + x⁵/120 (≈ 0.4794). Check against a calculator: sin(0.5) ≈ 0.4794. Each added term buys accuracy — and the one-term answer is already close, because 0.5 is near the centre 0 (Pakistan, Class 12, §2.17, ch-pp.74–78).

## Move the centre
Try the same trick for sin 31° about 0°: the Maclaurin series needs many terms, because 31° is far from 0. Now shift the centre to 30°, where sin and cos are known exactly (1/2 and √3/2), and take the step h = 1° ≈ 0.01745 radians: sin 31° ≈ 1/2 + h(√3/2) − h²(1/2)/2 ≈ 0.5150 — the book's own computation (Pakistan, Class 12, §2.17, ch-pp.78–81). Same function, better centre, three terms.

## Break the range on purpose
Put x = 2 into the series 1 − x + x² − x³ + … for 1/(1+x): the partial sums run 1, −1, 3, −5, … — they never settle. The series only copies the function for |x| < 1, as the book states (Pakistan, Class 12, §2.17, ch-pp.74–78). A series outside its range is not wrong arithmetic; it is no answer at all.
