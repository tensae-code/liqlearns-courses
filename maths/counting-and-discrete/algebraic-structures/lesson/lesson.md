# Algebraic structures — the lesson

Course: Maths · Stage: Stage 14 — Counting and Discrete Mathematics · Lesson: Algebraic structures
Built from: Yemen, Grade 10, Part 1 student book — Yemen, Grade 11, Science track, Part 1 student book — the sole source country for this lesson, as filed

## Do it first
Work with the set {0, 1, 2, 3} and clock addition — add, and if the answer passes 3, subtract 4 (so 2 + 3 = 1). Make the full 4×4 table. Now hunt: is there a row that copies the headings exactly? (There is: the 0 row.) And for 1, which element added to it brings you back to that special element? (3, since 1 + 3 = 0 in this clock world.) Without knowing it, you have checked the two ideas this lesson is built on: an **identity** and **inverses**. This lesson is Yemen's alone, as filed: its Grade 10 book teaches binary operations and the group (Unit 5, pp.96–110), and its Grade 11 Science book teaches rings and fields (Unit 1, pp.6–24).

## Then the explanation
**Binary operations.** A **binary operation** on a set S is a rule * that takes two elements of S and returns one element of S. Yemen's Grade 10 book opens its Algebraic structure unit here (5-1, Binary operations, p.96): addition and multiplication on the real numbers are the everyday examples, and any rule presented by a table — like your clock table — is one too, provided every answer stays inside the set. That last condition has a name: the operation is **closed** on S.

**Properties of a binary operation.** Yemen's next lesson (5-2, Properties of a binary operation, p.100) checks an operation for its properties. The working list: **closed** (answers stay in S); **commutative** (a * b = b * a for all a, b — the table is symmetric across its diagonal); **associative** ((a * b) * c = a * (b * c) for all a, b, c — the bracketing does not matter); an **identity** element e with e * a = a * e = a for every a; and, once an identity exists, an **inverse** for each a — an element a′ with a * a′ = e.

Tip — from us, not from the books. Check the cheap properties first. Closure and commutativity can be read off a table in seconds; associativity is the expensive one — it must hold for every triple, so it is the one worth testing on the triples that look most likely to break.

**The mathematical system.** Yemen's 5-3 (The mathematical system, p.108) names the whole package: a set together with an operation (or operations) and the properties they satisfy is a **mathematical system**. Naming the package is what lets the next lessons name special packages.

**The group.** Yemen's 5-4 (The group, p.110) states the axioms: a system (S, *) is a **group** when the operation is associative, there is an identity element, and every element has an inverse. If the operation is also commutative, the group is **abelian**, after Abel. Your clock-addition system {0, 1, 2, 3} passes all the tests: it is an abelian group, with identity 0 and inverses 0↔0, 1↔3, 2↔2. Subtraction on ℤ fails associativity — (5 − 3) − 1 = 1 but 5 − (3 − 1) = 3 — so (ℤ, −) is not a group, however familiar it feels.

**The ring.** Yemen's Grade 11 Science book opens with The ring and the field (Unit 1, p.6): a review and introduction (1-1, p.6), then **The ring** (1-2, p.14) with the book's own definition — a system (S, *, ∘) is a **ring** if (S, *) is an abelian group, ∘ is associative on S, and ∘ distributes over *. Its standing example: (ℤ, +, ×) is a ring — addition makes ℤ an abelian group, multiplication is associative, and multiplication distributes over addition, a × (b + c) = a×b + a×c.

**The field.** **The field** (1-3, p.21) adds the missing piece: in a field, the non-zero elements also have inverses under the second operation, so you can divide by anything except zero. Yemen closes the unit with **The field of real numbers** (1-4, p.24): ℝ, with + and ×, is a field — every non-zero real number x has 1/x. The integers ℤ stop one step earlier: 2 has no multiplicative inverse inside ℤ, so ℤ is a ring but not a field. That one failure is the cleanest way to feel the ladder: group → ring → field, each step demanding more.

## Say it to your companion
Recite: "A group is associative, has an identity, and every element has an inverse; abelian adds commutative." Then your companion names a system — (ℤ, +), clock addition mod 4, (ℤ, −) — and you say group or not group, naming the axiom that fails when it fails. Swap roles for rings: "A ring is an abelian group under the first operation, associative under the second, with the second distributing over the first."

## Do It Yourself
1. Build the table for multiplication mod 5 on {1, 2, 3, 4}. Find the identity, and the inverse of each element (Yemen, Grade 10, 5-1, p.96; 5-2, p.100).
2. Decide, with a reason for each, whether each system is a group: (ℤ, +); (ℤ, −); ({0, 1, 2, 3}, clock addition) (Yemen, Grade 10, 5-4, p.110).
3. In clock addition mod 4, solve x + 3 = 1 using the inverse of 3 (Yemen, Grade 10, 5-4, p.110).
4. Check Yemen's ring definition for (ℤ, +, ×), one condition at a time, with a number example for distribution (Yemen, Grade 11 Science, 1-2, p.14).
5. Say why ℚ is a field but ℤ is not, naming the exact element that shows the difference (Yemen, Grade 11 Science, 1-3, p.21; 1-4, p.24).
