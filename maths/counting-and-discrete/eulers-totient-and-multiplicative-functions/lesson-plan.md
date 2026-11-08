<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Euler's Totient and Multiplicative Functions

**One thing:** a multiplicative function is one that splits over coprime factors — f(mn) = f(m)·f(n) whenever gcd(m, n) = 1 — and its most famous example is Euler's totient φ(m): the count of the numbers from 1 to m that share no factor with m, computable from the factors of m instead of by counting.

**Unit:** Counting and Discrete Mathematics (Unit 14). **Level 157** (North Macedonia merge, 2026-11-07).

**Why this lesson exists:** North Macedonia's Grade 12 Algebra elective (*АЛГЕБРА ЗА ТРЕТА ГОДИНА*, Theme 2 — Selected parts of number theory) teaches multiplicative functions as a named concept (§2.2, printed p. 28) and then Euler's function with its table, its values at primes and its multiplicativity (§2.5, printed p. 37). No other read book in the library teaches either: the congruences lesson carries this same book's §§2.3–2.9 — congruences, residue systems, the Euler–Fermat–Wilson theorems, Diophantine equations — but the totient itself was keyed by the reader as having no current lesson, and a search of the congruences lesson confirms it carries no φ and no multiplicative functions. So under the everything-goes-in ruling (2026-11-06) the topic gets its own lesson. It stands alone: the congruences lesson is a soft hint before it (and the home of the Euler's theorem that φ feeds), never a gate. The book's one error here is taught corrected: its Theorem 1 (printed p. 37) states multiplicativity for ALL m, n, dropping the coprimality condition — its own table on the same page contradicts the printed claim, since φ(4) = 2 ≠ φ(2)·φ(2) = 1 — while the proof it prints assumes gcd(m, n) = 1, so the theorem as proved is the correct one.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Multiplicative Functions** — what a multiplicative function is: f(mn) = f(m)·f(n) whenever m and n are coprime — the coprime condition is part of the definition, and nothing is promised when the factors share a factor. (Was the definition part of depth Layer 3.)
2. **Euler's Function: The Count and the Table** — what φ(m) counts — the numbers from 1 to m coprime to m — finding it by listing, and the book's table of φ(1) to φ(12), every entry checkable by listing. (Was depth Layer 1 and the table part of depth Layer 2.)
3. **Euler's Function at a Prime** — the prime rule φ(p) = p − 1, read off the table's prime rows: φ(2) = 1, φ(3) = 2, φ(5) = 4, φ(7) = 6, φ(11) = 10. (Was the prime part of depth Layer 2.)
4. **Computing by Splitting** — computing φ of a composite from a coprime split — φ(12) = φ(3)·φ(4) = 4 — including the bigger values beyond the table, such as φ(36) = φ(4)·φ(9) = 12, which stand in this sub lesson's text. (Was the computing part of depth Layer 3, and depth Layer 5.)
5. **The Printed Slip — and the Repair** — the book's printed Theorem 1, which claims the split for all m, n, caught by the book's own table at m = n = 2: φ(4) = 2 against φ(2)·φ(2) = 1 — and the theorem taught corrected, with 'coprime' restored. (Was depth Layer 4.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## The climb

1. **Multiplicative functions.** A function f on the natural numbers is multiplicative when f(mn) = f(m)·f(n) for **coprime** m and n. The word "coprime" is load-bearing: nothing is promised when m and n share a factor.
2. **Euler's function.** φ(m) counts the elements of a reduced residue system modulo m — the numbers from 1 to m that are coprime to m. By hand: the numbers coprime to 10 are 1, 3, 7, 9, so φ(10) = 4.
3. **The table.** The book prints φ(1)…φ(12) = 1, 1, 2, 2, 4, 2, 6, 4, 6, 4, 10, 4 — every value checkable by listing, and the raw material for everything after.
4. **Primes.** φ(p) = p − 1 for prime p: every number from 1 to p − 1 is coprime to p. So φ(7) = 6 and φ(11) = 10 straight off.
5. **Splitting.** Because φ is multiplicative, a composite value comes from its coprime factors: φ(12) = φ(3)·φ(4) = 2·2 = 4, and φ(36) = φ(4)·φ(9) = 2·6 = 12 — no listing of dozens of numbers needed.
6. **The printed slip, caught by the table.** The book's Theorem 1 claims the splitting for all m, n. Try m = n = 2: φ(2·2) = φ(4) = 2, but φ(2)·φ(2) = 1·1 = 1. The table itself refutes the statement; with "coprime" restored — the hypothesis the book's own proof uses — the theorem stands.

## Add-on slots

- slot-totient-0 (IMAGE): the numbers 1 to 12 in a row with the ones coprime to 12 (1, 5, 7, 11) lit up and counted: φ(12) = 4. What the student does: repeats the lighting for 10 (1, 3, 7, 9) and says φ(10) aloud before the count is shown.
- slot-totient-1 (GIF, 1–2 s): the φ table 1…12 building up value by value, then the cell φ(4) = 2 flashing next to φ(2)·φ(2) = 1 with a "not equal" sign. What the student does: explains in one sentence why the two cells kill the claim that φ splits over ALL factors.
- slot-totient-2 (IMAGE): 36 splitting into the coprime pair 4 and 9, with φ(4) = 2 and φ(9) = 6 underneath and the product 12 as the result. What the student does: performs the same trick on 12 = 3 × 4 and checks the answer against the table.
