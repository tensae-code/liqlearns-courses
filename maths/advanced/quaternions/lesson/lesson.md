# Quaternions — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Quaternions
Built from: China, Mathematics Compulsory Volume 4 (B edition), Chapter 10 extended reading (printed pp.47–48) — the sole source, an extended reading as filed

## Do it first
You know i, the imaginary unit with i² = −1, and complex numbers a + bi. Ask the dangerous question: what if there were a second imaginary unit — call it j — also with j² = −1, and different from both 1 and i? What would ij be? It cannot be 1, −1, i or j without breaking the rules you already have. China's B-edition Compulsory Volume 4 book poses exactly this extension at the end of its complex-numbers chapter, as an **extended reading** (Ch.10, printed pp.47–48) — two pages, filed as an extended reading, and this small lesson follows those two pages honestly and stops where they stop.

## Then the explanation
**The form.** A **quaternion** is a number

q = a + bi + cj + dk,

with a, b, c, d real: one **real part** a and three **imaginary parts** along three separate units i, j, k. Where a complex number has two parts, a quaternion has four — the reading presents it as the next step of the same number-system expansion that produced the complex numbers (Ch.10 extended reading, printed pp.47–48).

**The defining rules.** The three units obey

i² = j² = k² = −1,

and their pairwise products are fixed by the cycle

ij = k,   jk = i,   ki = j.

(Indeed the three rules compress into one line the reading's system is known by: i² = j² = k² = ijk = −1.) Addition and subtraction go part by part, exactly as for complex numbers: match the 1s, the i's, the j's and the k's (printed pp.47–48).

**Multiplication does not commute.** Reverse any product in the cycle and the sign flips:

ji = −k,   kj = −i,   ik = −j.

So ij ≠ ji: quaternion multiplication is **non-commutative** — the reading's headline fact (printed pp.47–48). The order of the factors is part of the answer. Worked in full: (1 + i)(1 + j) = 1 + i + j + ij = 1 + i + j + k, while (1 + j)(1 + i) = 1 + i + j + ji = 1 + i + j − k. The two products agree in three parts and disagree in the fourth — a number system can survive losing commutativity, and this one does.

**Conjugate and modulus.** The complex patterns extend. The **conjugate** of q = a + bi + cj + dk flips all three imaginary signs: q̄ = a − bi − cj − dk. The **modulus** is the four-part distance |q| = √(a² + b² + c² + d²), and as with complex numbers, q·q̄ = |q|², a real number — for q = 1 + 2i − j + 2k, that is 1 + 4 + 1 + 4 = 10, so |q| = √10 (printed pp.47–48, read with the chapter's complex-number work on conjugates and moduli).

Tip — from us, not from the books. Keep the cycle as a picture: i → j → k → i around a triangle. With the arrows: positive (ij = k, jk = i, ki = j). Against the arrows: negative. Every sign in quaternion multiplication is that one picture.

**Where the reading ends.** The reading is an invitation, not a course: it defines the system, shows the multiplication and its non-commutativity, and stops. This lesson stops with it. Quaternions earn their place in the course because one country's book chose to print them for every pupil following the B-edition — as enrichment at the edge of the complex numbers, which is exactly how this lesson teaches them.

## Say it to your companion
State a quaternion's four parts and the rules i² = j² = k² = −1. Then prove non-commutativity in one breath: ij = k but ji = −k, so order matters. Your companion then asks you any two unit products, forwards and backwards around the cycle, and you answer with signs.

## Do It Yourself
1. Write the real part and the three imaginary parts of q = 3 − i + 4j − 2k.
2. Add (2 + i − 3k) and (1 − 2i + j + k) part by part.
3. Give all six products ij, jk, ki, ji, kj, ik from the cycle, with signs.
4. Multiply (2 + j)(1 + k) and then (1 + k)(2 + j); show the answers differ (extended reading, printed pp.47–48).
5. Find the conjugate and the modulus of q = 2 + i + 2j + k.
