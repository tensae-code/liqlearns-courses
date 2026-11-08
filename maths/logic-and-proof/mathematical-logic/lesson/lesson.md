# Mathematical Logic — the lesson

Course: Maths · Unit: Unit 13 — Logic and Proof · Lesson: Mathematical Logic
Built from: Laos, Grade 10 student book — Armenia, Grade 12 logic book and Grade 11 Algebra and Analysis (both streams) — Iraq, Grade 10 Scientific — Greece, Grade 10 Algebra — Cambodia, Grade 10 Part 1 — Yemen, Grade 10 Part 1 — Sierra Leone, SSS 2 Term 1 pupil handbook — Iran, Grade 11 Statistics and Probability and Mathematics and Statistics (2) — Vietnam, Toán 10 Tập Một — Kazakhstan, Grade 1

## Do it first
Judge these six sentences — true, false, or neither:
1. "Taiz is a city in Yemen."
2. "7 = 4 + 5."
3. "Close the door."
4. "What time is it?"
5. "Every even number is divisible by 2."
6. "There is a number whose square is 16."

The first two and the last two can be judged; the middle two cannot. Yemen's Grade 10 book opens its logic unit with exactly the first pair — "Taiz is a city in Yemen" is true, 7 = 4 + 5 is false (Grade 10 Part 1, Unit 1, p.7). Sentences that can be judged are the raw material of this whole lesson.

## Then the explanation

## Sub lesson 1 — Propositions and Connectives

**Propositions.** A proposition is a sentence that is either true or false — it has a truth value, T or F. Questions, commands, requests and exclamations are not propositions, because none of them can be true or false. Laos's Grade 10 book opens its logic chapter with this sort (Ch.I L1, p.1), Sierra Leone's SSS 2 handbook teaches simple statements — open and closed — and judging their truth (Term 1, L41, p.107), and Vietnam's Grade 10 book opens its whole first chapter with propositions (Toán 10 v1, Ch.I Bài 1, p.5). Armenia's Grade 12 logic book is a whole book on this one topic, opening with statements, true and false (p.9). Even Kazakhstan's Grade 1 book plants the seed: its glossary carries "statement (true/false)" and its problem lessons include logic problems (Grade 1, pp.124–144).

**The connectives.** Propositions join into compound propositions:
- ~p (or ¬p): **not** p — flips the truth value.
- p∧q: p **and** q — true only when both are true.
- p∨q: p **or** q — true when at least one is true.
- p xor q: **exclusive or** — true when exactly one is true.
- p⇒q: **if** p **then** q — false in exactly one case: p true and q false.
- p⇔q: p **if and only if** q — true when p and q match.

Laos's book gives the connectives as one summary table with the circuit pictures: "and" is two switches in series (the lamp lights only when both are closed), "or" is two switches in parallel (Grade 10, Ch.I L1, pp.1–13). Iraq's Grade 10 Scientific book gives "if…then" and "if and only if" their own sections (Ch.1 §§1-2, 1-3, pp.4–20). Greece's Grade 10 Algebra book opens with the vocabulary of logic — implication, equivalence and negation in elementary form (introductory chapter, pp.9–12). Armenia's Grade 11 books name the same joins the "logical sum" (∨) and "logical product" (∧), each with its negation (general stream, Ch.3 §1, p.42; natural-mathematics stream, Ch.3 §1, p.51), and Iran's two Grade 11 books build all four compound forms with truth tables (Statistics and Probability, Ch.1, pp.2–11; Mathematics and Statistics (2), Ch.1, pp.2–11).

## Sub lesson 2 — Truth Tables, Equivalence and De Morgan

**Truth tables.** A truth table lists every case. One proposition: 2 rows. Two: 4 rows. Three: 8 rows. In general n propositions give 2ⁿ rows — Laos's book states the 2ⁿ rule outright (Ch.I L1). To find the truth value of a compound proposition, work from the smallest joins outward — or use the tree method Laos's book teaches beside the table. Sierra Leone's handbook shows conjunction and disjunction on truth tables (SSS 2 Term 1, L45, p.115).

Tip — from us, not from the books. Build the table's first columns in a fixed rhythm — for two propositions: TT, TF, FT, FF. If the rhythm never changes, no row is ever lost or doubled.

**Equivalence and De Morgan.** Two compound propositions are equivalent (≡) when their truth tables match in every row. The laws every book keeps:
- ~(p∨q) ≡ ~p∧~q and ~(p∧q) ≡ ~p∨~q — **De Morgan's laws**.
- (p⇒q) ≡ ~p∨q.
- (p⇒q) ≡ (~q⇒~p) — the **contrapositive** says the same thing.
- p⇔q ≡ (p⇒q)∧(q⇒p).

Laos proves each by truth table (Grade 10, Ch.I L2, p.14). Cambodia's Grade 10 book works truth tables from p.3 and reaches De Morgan's laws at p.17 (Part 1, Ch.1, pp.2–17). Yemen's Grade 10 book teaches logical equivalence with tables of its own — p, ~p, ~(~p), and a∧b ≡ b∧a (Unit 1 §1-3, p.16). Armenia's Grade 12 book treats the negations of the sum and the product as their own sections (pp.14, 19).

**Tautology and contradiction.** A compound proposition true in every row is a tautology; one false in every row is a contradiction. Laos's examples: modus ponens in symbols, ((p⇒q)∧p)⇒q, is a tautology, and (p∧q)∧~q is a contradiction (Grade 10, Ch.I L2, pp.14–19).

## Sub lesson 3 — Quantifiers, Open Sentences and Inference

**Open sentences and quantifiers.** "x + 3 = 7" is neither true nor false until x is fixed — it is an open sentence, written P(x). Two signs close it:
- ∀x, P(x): **for all** x, P(x) — true only if it holds for every x.
- ∃x, P(x): **there exists** an x with P(x) — true if one x is enough.

Their negations swap the sign and negate the inside: ~(∀x, P(x)) is ∃x, ~P(x), and ~(∃x, P(x)) is ∀x, ~P(x). Laos teaches open sentences, both quantifiers and both negation rules in one lesson (Ch.I L3, p.20); Iraq gives quantified propositions and their negations a section of its logic chapter (Ch.1 §1-7); Iran's Statistics and Probability book teaches quantifiers at p.11 and negating quantified propositions at p.13. Yemen closes its logic unit with quantifiers too (Unit 1 §1-5, p.22).

**Definition, axiom, theorem — and the converse.** Armenia's Grade 12 book separates the furniture of mathematics: a definition says what a word means; an axiom is accepted without proof; a theorem is proved (p.24). It also separates a statement from its converse and its opposite (p.36): "if a number ends in 0, it is even" is true, but its converse — "if a number is even, it ends in 0" — is false (12 is the counterexample). Sierra Leone's handbook closes its logic block with equivalence, the chain rule and judging whether an argument is valid (SSS 2 Term 1, L46, p.118; L48, p.124) — the doorway into the next lesson, Proof Methods.

## Say it to your companion
Say a ∀ sentence about the room: "Every chair in this room is wooden." Your companion must answer with its exact negation — "There is a chair in this room that is not wooden" — not with "no chair is wooden." Then trade: one of you builds p⇒q from two true-or-false sentences, the other says the one row that would make it false, and then says its contrapositive.

## Do It Yourself
1. Sort these into proposition / not a proposition, with truth values where they apply: "9 is a prime number." "Please open the book." "There is an even prime number." "How old are you?"
2. With p true and q false, give the truth value of p∧q, p∨q, p⇒q, q⇒p, p⇔q and ~(p∨q).
3. Build the full truth table for (p∧~q) and say whether it is a tautology, a contradiction, or neither.
4. Use De Morgan to rewrite ~(p∧~q) without a "not" outside brackets, and check your answer against your table from task 3.
5. Negate both sentences: "Every pupil passed." "There is a number greater than its own square."
