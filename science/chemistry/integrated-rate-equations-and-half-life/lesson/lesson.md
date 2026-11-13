# Integrated rate equations and half-life

## Do it first
Before you read: a reaction starts with 1.00 mol of reactant. After ten minutes 0.60 mol remains; after twenty, 0.36 mol; after thirty, about 0.216 mol. Say out loud: is the amount falling by the same *amount* each ten minutes, or by the same *fraction* — and could you predict the amount at one hour without watching the clock? Then read on: India's NCERT Class XII book turns the rate law into **integrated rate equations** (§4.3) — equations that give the concentration at any time directly, and with them the half-life.

## Sub lesson 1 — Zero order — the straight-line fall

For a **zero-order reaction** the rate does not depend on the concentration at all: rate = k, a constant, until the reactant runs out. Integrating gives the straight line:

**[R] = [R]₀ − kt**

The concentration falls by **equal amounts in equal times** — NCERT's examples are the surface reactions that run at a pace the surface sets, such as the decomposition of ammonia on a hot platinum surface and of hydrogen iodide on gold. A plot of [R] against t is a straight line of slope −k, and the units of k are the units of rate itself: **mol L⁻¹ time⁻¹**.

The **half-life** — the time for the concentration to fall to half its starting value — follows by setting [R] = [R]₀/2:

**t½ = [R]₀ / 2k**

Note what it hangs on: the starting concentration. Start a zero-order reaction with twice as much and its half-life doubles — the constant pace has twice as far to go.

## Sub lesson 2 — First order — the logarithmic fall

For a **first-order reaction** the rate is proportional to the concentration: rate = k[R]. The fall is by **equal fractions in equal times** — your Do-it-first numbers (1.00 → 0.60 → 0.36 → 0.216, ×0.6 each step) are a first-order fall. Integrating gives:

**k = (2.303 / t) · log ( [R]₀ / [R] )**, equivalently **log [R] = log [R]₀ − kt/2.303**

A plot of log [R] against t is a straight line of slope −k/2.303; the units of k are simply **time⁻¹**. NCERT's examples: the decomposition of N₂O₅ and of hydrogen peroxide in solution run first-order, as does every radioactive decay. With the equation, any point of the fall can be computed from any other — concentration at a time, or time to a chosen concentration — without measuring the whole curve.

## Sub lesson 3 — Half-life, and the pseudo-first-order disguise

Set [R] = [R]₀/2 in the first-order equation and the starting concentration cancels:

**t½ = 0.693 / k**

The half-life of a first-order reaction is **constant** — independent of how much you start with. Half falls in t½, half of the remainder in the next t½, and so on: after n half-lives the fraction remaining is **(½)ⁿ**. This is why the half-life is the natural clock of first-order change wherever it appears, from reaction vessels to radioactive samples — and its constancy is the field test for first order: measure t½ at two different starting concentrations; if it does not move, the reaction is first order.

One disguise remains. A reaction that is truly second order — rate = k[A][B] — behaves as first order when one reactant is present in **large excess**, because that concentration hardly changes and can be folded into the constant: rate ≈ k′[A], with k′ = k[B]₀. NCERT calls such reactions **pseudo first order**: the **hydrolysis of ethyl acetate** in excess water, and the **inversion of cane sugar**, are its examples — both followed as first-order reactions while the water stands effectively constant. §4.3's three tools — the two integrated equations and the two half-lives — are the calculating kit the rest of kinetics uses.

## The key ideas

- **Zero order**: [R] = [R]₀ − kt (straight-line fall, equal amounts); **t½ = [R]₀/2k** — depends on the starting concentration; k in mol L⁻¹ time⁻¹.
- **First order**: k = (2.303/t) log ([R]₀/[R]) (equal fractions); **t½ = 0.693/k** — **independent** of the starting concentration; k in time⁻¹; fraction left after n half-lives is (½)ⁿ.
- The constancy of t½ at different starting concentrations is the test for first order.
- **Pseudo first order**: a higher-order reaction with one reactant in large excess (ethyl acetate hydrolysis, cane-sugar inversion) follows the first-order equation with the excess folded into k′.

## Say it to your companion
Explain integrated rates to your companion in your own words: write both integrated equations and both half-lives, say which fall is by amounts and which by fractions, prove from the equations why only one half-life is constant, and finish with the excess-reactant disguise and its two NCERT examples.

## Do It Yourself
1. A zero-order reaction has k = 3.0 × 10⁻³ mol L⁻¹ s⁻¹ and starts at 0.60 mol L⁻¹. Find [R] after 100 s and the half-life. ([R] = 0.60 − 0.30 = 0.30 mol L⁻¹; t½ = 0.60/(2 × 3.0 × 10⁻³) = 100 s — consistent: after one half-life, half remains.)
2. A first-order reaction is 90% complete in 100 minutes. Show its half-life is about 30 minutes. (k = (2.303/100) log(100/10) = 0.02303 min⁻¹; t½ = 0.693/0.02303 ≈ 30 min.)
3. A reaction's half-life is measured at two starting concentrations and comes out different. What is ruled out, and why? (First order is ruled out: its t½ = 0.693/k contains no [R]₀, so it cannot change with the starting concentration.)
