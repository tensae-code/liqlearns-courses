# Writing algorithms — worked problems

## Do it first

One problem, alone first: read three numbers and display the greatest. Write your algorithm. Stuck halfway is fine — this lesson works five problems in full, and yours is the second of them. Compare your attempt when you reach it: where did the keyed solution's move differ from yours?

## Problem 1 — area of a triangle, two ways

**From base and height:** read base and height; **area = ½ × base × height**; display the area.

**From the three sides** (any triangle): read side1, side2, side3; compute the semi-perimeter **s = (side1 + side2 + side3) / 2**; then **area = the square root of s × (s − side1) × (s − side2) × (s − side3)**; display the area.

## Problem 2 — the greatest of three numbers

Read the three numbers. Keep a variable, **largest**. Compare the numbers **one against another in a chain**, moving the bigger value into **largest** at each comparison; at the end, **display largest**. The keyed solution is drawn as a flowchart as well as written — the comparisons are decisions, one after another.

## Problem 3 — is it prime? Count the divisors

Read **N**. Set a **count to 0**. **Loop** a trial divisor from **2 to N**: whenever the trial divides N exactly, **add 1 to the count**. At the end: a **count of zero means prime**; any count above zero means not prime.

One note travels with the key: **2 is the only even prime**. Watch the counting loop in the GIF — the loop is the mechanism.

[GIF 15735 — the prime-check loop testing one number after another and counting]

## Problem 4 — roots of a quadratic equation

Read **a, b, c**. First compute the **discriminant: D = b² − 4ac** — it is what **tells the roots' nature**, so the algorithm branches on it:

- **D above zero** → **two real, different roots**, found by the **quadratic formula**.
- **D equal to zero** → the **equal-roots** case.
- **D below zero** → no real roots by this route.

The keyed solution draws the flowchart for this branching — one diamond, three ways out.

[Picture 15734 — the discriminant fork]

## Problem 5 — RESULT = (U + V²) / W

Read **U, V, W**. Compute **RESULT = (U + V²) / W** — mind the order: **square V first**, add U, then divide by W. Display RESULT. The key gives both the **algorithm and its flowchart** for this one.

## Say it to your companion

Work one problem aloud for your companion from the first read to the display — they follow with the lesson open and stop you at any step the key does differently.

## Do It Yourself

1. Run problem 3 by hand on N = 11 and N = 12. Write the count at the end of each.
2. A quadratic has b² − 4ac = 0. Which branch runs, and what kind of roots come out?
3. For U = 3, V = 2, W = 7: compute RESULT step by step, naming the order of operations.
