# Congruences and Diophantine equations — the lesson

Course: Maths · Unit: Unit 14 — Counting and Discrete Mathematics · Lesson: Congruences and Diophantine equations
Built from: Iran, Discrete Mathematics, Grade 12 (Mathematical Sciences branch) — Greece, Mathematics, Grade 11 orientation book (W7) — Sierra Leone, SSS 1 Pupils' Handbook, Term 1 — Kazakhstan, Grade 6, Grade 8 and Grade 9 books

## Do it first
Today is a Friday. What day of the week will it be in 100 days? Do not count day by day. Divide 100 by 7: 100 = 14 × 7 + 2. The 14 whole weeks bring you back to Friday; only the remainder, 2, moves you: Saturday, Sunday. In 100 days it will be a Sunday. You have just done modular arithmetic: only the remainder mattered. Sierra Leone's SSS 1 handbook introduces modular arithmetic exactly here — cyclic events, days and clocks (L21, p.59) — and Iran's Discrete Mathematics book uses congruences for the same calendar computation (p.24).

## Then the explanation

## Sub lesson 1 — Remainders and a Modulus

**Remainders and a modulus.** Fix a number m, the **modulus**. Every whole number leaves a remainder on division by m, and that remainder can be taken between 0 and m − 1: this is the number's **simplest form** in the modulus, the subject of Sierra Leone's L22 (p.62). Sierra Leone's L23 (p.65) then does addition, subtraction and multiplication inside a modulus: work out the ordinary answer, then reduce it. Its L24 (p.68) applies the same idea to real-life cyclic problems.

## Sub lesson 2 — Congruences, Tests and Euclid's Algorithm

**Congruences.** Two numbers are **congruent modulo m**, written a ≡ b (mod m), when they leave the same remainder on division by m — equivalently, when m divides a − b. Iran's book defines the congruence this way and builds it on the division theorem and residue classes (pp.15–18). Congruences behave almost like equations: you may add, subtract and multiply congruences with the same modulus. **Cancellation needs care**: from ca ≡ cb (mod m) you may only conclude a ≡ b (mod m / gcd(c, m)) — divide the modulus through by gcd(c, m) too. Iran's book flags the failure of plain cancellation by a counterexample and states the corrected rule without proof, in the book's own words "we accept this property without proof" (p.22).

Tip — from us, not from the books. When a modulus problem feels big, shrink every number to its simplest form FIRST, before you add or multiply. Small numbers make small mistakes.

**Tests and the calendar.** Because 10 ≡ 1 (mod 9), a number is congruent mod 9 to the sum of its digits — Iran derives this digit-sum divisibility test from congruences in full (p.23), the old "casting out nines" check. The same trick with mod 7 runs the day-of-the-week computation you did at the start (Iran, p.24).

**Euclid's algorithm.** The greatest common divisor of two big numbers is slow to find by listing factors. **Euclid's algorithm** divides instead: gcd(a, b) = gcd(b, remainder of a ÷ b), repeated until the remainder is 0; the last non-zero remainder is the gcd. Kazakhstan's Grade 8 book teaches the algorithm in its starred additional-materials chapter on real numbers — positional systems, divisibility tests, primes, the fundamental theorem of arithmetic, gcd and lcm from prime factorisations (worked: GCD(680, 612) = 68), division with remainder, and Euclid's algorithm (§§6.1–6.5, pp.160–177). That chapter is starred OPTIONAL in its book, as filed — this lesson keeps it, marked the same way. Note the honest split between the books: Iran's Discrete book does NOT teach a Euclidean algorithm or a Bézout identity — its gcd work stays with definitions (p.13) — so this lesson takes the algorithm from Kazakhstan, as filed.

## Sub lesson 3 — Linear Congruences and Diophantine Equations

**Linear congruences.** Solving ax ≡ b (mod m) means finding every x with that property. Iran solves linear congruences and gives their general solutions (p.25): a solution exists exactly when gcd(a, m) divides b, and then the solutions repeat every m / gcd(a, m). Its exercise set includes congruences of the shape 423x ≡ 79 (mod 11) (p.30).

**Diophantine equations.** A **Diophantine equation** asks for whole-number solutions. The linear one, ax + by = c, is the heart of this lesson: Greece's Grade 11 orientation book teaches it inside its number-theory chapter, after Euclidean division, divisibility, gcd and lcm, primes and congruent numbers (Ch.4, pp.135–184). The rule: solutions exist exactly when gcd(a, b) divides c. Iran solves the same equation by turning it into a congruence — ax + by = c becomes a congruence in one unknown — then gives the **general integer solution** and picks out the **non-negative solutions** in applied money-and-weights problems (pp.26–29). Once one solution (x₀, y₀) is known, all of them are x = x₀ + (b/d)t, y = y₀ − (a/d)t, where d = gcd(a, b) and t is any integer. Kazakhstan's Grade 9 Soltan book works two-digit-number problems by a Diophantine enumeration as one of its two ways (Algebra 9, Ch.1, §3, p.34), and its Grade 6 book builds the equation x + y = 3(x − y) and the matchstick equation 3y + 4x = 30 — 30 matchsticks made into triangles (y) and squares (x) — whose whole-number solutions are only (x, y) = (3, 6) and (6, 2) (§10.1, p.178).

## Say it to your companion
Say: "a ≡ b (mod m) means a and b leave the same remainder when divided by m." Then explain why 100 days from Friday is a Sunday, using only the remainder 2. Swap: your companion explains the gcd check that decides whether ax + by = c can be solved at all, and you check them.

## Do It Yourself
1. Reduce to simplest form: 47 in mod 5; −3 in mod 7; 100 in mod 9 (Sierra Leone, L22, p.62).
2. Compute in mod 6: (4 + 5) mod 6; (4 × 5) mod 6; (2 − 5) mod 6 (Sierra Leone, L23, p.65).
3. Use the digit-sum rule to decide whether 9 divides 7,254, and check by division (Iran, p.23).
4. Find gcd(252, 198) by Euclid's algorithm, then by prime factorisations; compare the work (Kazakhstan, Grade 8, starred chapter, pp.160–177 — optional as filed).
5. Solve 3x + 5y = 22 in non-negative whole numbers, Iran's way: turn it into a congruence, give the general solution, then keep only the non-negative ones (Iran, pp.26–29).
