# Hands-on — Euler's Totient and Multiplicative Functions

## Activity 1 — Build the table by hand (15 minutes)

For each m from 1 to 12, write the numbers 1 to m and cross out every one that shares a factor with m. Count what survives. You should rebuild North Macedonia's Grade 12 Algebra book's printed table exactly: φ(1)…φ(12) = 1, 1, 2, 2, 4, 2, 6, 4, 6, 4, 10, 4 (printed p. 37). Circle the primes in your table — 2, 3, 5, 7, 11 — and check each one against the rule φ(p) = p − 1.

## Activity 2 — Split, don't count (10 minutes)

Compute φ(12) three ways. First by listing: the numbers coprime to 12 are 1, 5, 7, 11, so φ(12) = 4. Then by the split: 12 = 3 × 4 with 3 and 4 coprime, so φ(12) = φ(3)·φ(4) = 2·2 = 4 — the same, with no listing past 4. Last, try the illegal split 12 = 2 × 6: φ(2)·φ(6) = 1·2 = 2 ≠ 4. Write one sentence on why this split is not owed anything: 2 and 6 are not coprime. This is the multiplicativity skill of the book's §§2.2 and 2.5 (printed pp. 28 and 37).

## Activity 3 — Catch the book's slip (10 minutes)

The book's Theorem 1 (printed p. 37) says: "φ is multiplicative, that is, φ(m·n) = φ(m)·φ(n) for all m, n." Using only the table from Activity 1, find the smallest counterexample. (Answer: m = n = 2 — φ(2·2) = φ(4) = 2, but φ(2)·φ(2) = 1·1 = 1.) Then repair the theorem in writing: the correct statement adds the hypothesis gcd(m, n) = 1 — the very hypothesis the book's printed proof begins with. The lesson teaches the repaired version.
