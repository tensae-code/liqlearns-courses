# Euler's Totient and Multiplicative Functions

## You do it first

Write down the numbers from 1 to 10. Cross out every number that shares a factor with 10 — every even number, and 5. What is left?

1, 3, 7, 9 — four numbers. That little count, "how many numbers up to m share nothing with m", turns out to be one of the most useful counts in number theory. It has a name, a table, and a shortcut — and one famous printed mistake, which this lesson catches with the book's own table.

## Sub lesson 1 — Multiplicative Functions

North Macedonia's Grade 12 Algebra book (Theme 2, Selected parts of number theory) first names a class of functions. A function f on the natural numbers is **multiplicative** when

**f(mn) = f(m)·f(n) whenever m and n are coprime** (gcd(m, n) = 1).

The promise is deliberately narrow: the value at a product comes from the values at the factors **only when the factors share nothing**. When m and n have a common factor, the function owes you no such split. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.2, printed p. 28.)

## Sub lesson 2 — Euler's Function: The Count and the Table

The book's central example is **Euler's function** (Euler's totient), written φ(m): it **counts the elements of a reduced residue system modulo m** — in plain words, the count of the numbers from 1 to m that are coprime to m. Your opening count was exactly this: the numbers coprime to 10 are 1, 3, 7, 9, so **φ(10) = 4**. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.5, printed p. 37.)

The book prints the first twelve values:

| m | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| φ(m) | 1 | 1 | 2 | 2 | 4 | 2 | 6 | 4 | 6 | 4 | 10 | 4 |

Every entry can be checked by listing: for 8, the coprime numbers are 1, 3, 5, 7 — four of them, and the table says φ(8) = 4. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.5, printed p. 37.)

## Sub lesson 3 — Euler's Function at a Prime

Read the prime rows of the table: φ(2) = 1, φ(3) = 2, φ(5) = 4, φ(7) = 6, φ(11) = 10. The pattern is the theorem:

**φ(p) = p − 1 for prime p** —

nothing from 1 to p − 1 shares a factor with a prime, so everything counts. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.5, printed p. 37.)

## Sub lesson 4 — Computing by Splitting

φ is multiplicative, and that is the working tool. To find φ(12), do not list twelve numbers: split 12 = 3 × 4 into coprime factors and multiply the values from the table:

φ(12) = φ(3)·φ(4) = 2·2 = **4** —

which the table confirms. Bigger game works the same way: φ(36) = φ(4)·φ(9) = 2·6 = **12**, from one coprime split (4 and 9 share nothing) and two table lookups. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.5, printed p. 37.)

## Sub lesson 5 — The Printed Slip — and the Repair

The book's Theorem 1 (printed p. 37) states: "Euler's function φ is multiplicative, i.e. φ(m·n) = φ(m)·φ(n) **for all m, n**." As printed, that is false — and the table on the very same page refutes it. Take m = n = 2:

φ(2·2) = φ(4) = **2**, but φ(2)·φ(2) = 1·1 = **1**.

The factors 2 and 2 are not coprime, so no split was owed. The proof printed right after the theorem begins "let gcd(m, n) = 1" — the hypothesis the statement dropped. **Taught corrected, the theorem reads: φ(mn) = φ(m)·φ(n) for coprime m and n.** (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §2.5, printed p. 37.)

Why the lesson bothers with one function: in the very next unit of the same book (§2.6), φ powers Euler's theorem, a^φ(m) ≡ 1 (mod m) — you will meet it in the congruences-and-diophantine-equations lesson, where the rest of this book's number-theory theme lives.

## Do it yourself

1. By listing, find φ(9) and check it against the table. (The coprime numbers are 1, 2, 4, 5, 7, 8 — φ(9) = 6.)
2. Give φ(13) at once, and name the rule you used. (12, by φ(p) = p − 1.)
3. Compute φ(20) by a coprime split, using only table values. (20 = 4 × 5, coprime: φ(4)·φ(5) = 2·4 = 8.)
4. A classmate writes φ(16) = φ(2)·φ(8) = 1·4 = 4. Find both mistakes: the split itself, and what φ(16) really is. (2 and 8 are not coprime, so the split is not licensed; listing gives φ(16) = 8.)
5. State Theorem 1 the way it should have been printed, and name the table entry that proves the printed version wrong.
