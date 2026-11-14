# Boolean Laws and De Morgan's Theorems

## Do it first

Write the expression A + A·B and build its four-row truth table. Row by row you find the output is exactly A, every time: when A is 1 the answer is 1 whatever B does, and when A is 0 both terms are 0. The term A·B does nothing at all. That is not luck — it is one of the laws of Boolean algebra, and builders earn their living with these laws: every gate thrown away is money, space and power saved. This lesson teaches the laws, and De Morgan's two theorems, the pair that does the heaviest work of all.

## Sub lesson 1 — The laws of Boolean algebra

A law of Boolean algebra is a promise: two expressions are equal — same truth table — for *every* value of the variables. Learn them as tools, one handle each.

**Commutative:** A + B = B + A and A · B = B · A. Order does not matter.
**Associative:** (A + B) + C = A + (B + C), and the same for AND. Grouping does not matter.
**Distributive:** A · (B + C) = A·B + A·C — AND spreads over OR, as in ordinary algebra. Boolean algebra has a second distributive law ordinary algebra does not: A + B·C = (A + B) · (A + C). OR spreads over AND too. Do not assume a law from school algebra — prove it here by truth table once, then use it freely.
**Identity:** A + 0 = A and A · 1 = A. Adding 0 or multiplying by 1 changes nothing.
**Null (dominance):** A + 1 = 1 and A · 0 = 0. A single 1 settles an OR; a single 0 settles an AND.
**Complement:** A + Ā = 1 and A · Ā = 0. A thing or its opposite is everything; a thing and its opposite is nothing.
**Idempotent:** A + A = A and A · A = A. Saying it twice changes nothing.
**Absorption:** A + A·B = A. The second term is swallowed by the first — the law from the opening of this lesson.

[Picture — the laws laid out as a toolbox chart, each law with its pair of expressions and a one-line saying: 'order does not matter', 'a single 1 settles an OR', and so on]

Every one of these is proved the same way: build the truth table of the left side and of the right side and see the columns match. Prove each law once in your life; after that, use it as a tool and spend your effort on choosing *which* law shortens the expression in front of you. Simplifying always goes: look for a complement pair, look for absorption, factor with distribution — and check the final answer with a truth table.

## Sub lesson 2 — De Morgan's theorems — and simplifying with all the laws together

Two laws do more work in real circuits than all the others together. They belong to Augustus De Morgan, and they say what a bar over a whole bracket really means.

**First theorem:** the negation of an OR is the AND of the negations:
**NOT (A + B) = (NOT A) · (NOT B)** — in symbols, the bar over (A + B) equals Ā · B̄.
Check it on the row A = 0, B = 1: the left side is NOT 1 = 0; the right side is 1 · 0 = 0. The full four-row table matches, and the saying proves itself in words: 'not (A or B)' means *neither* — not A *and* not B.

**Second theorem:** the negation of an AND is the OR of the negations:
**NOT (A · B) = (NOT A) + (NOT B)** — the bar over (A·B) equals Ā + B̄.
In words: 'not (both)' means at least one is missing — not A *or* not B.

[Picture — De Morgan's rule drawn as a bar breaking over a bracket: the long bar splits into short bars over each letter, and the operation inside flips, + becoming · and · becoming +]

The working picture: **break the bar, and change the operation.** Push a long bar through a bracket and it lands as short bars on each letter, while + turns into · and · turns into +. Apply it step by step, one bar at a time, from the outside in: the bar over (A · B̄ + C) first becomes (bar over A·B̄) · C̄, then (Ā + B) · C̄. These theorems matter far beyond paper: they say an AND built from negated inputs *is* an OR, and that is how real gates are swapped for each other in the gates lesson. As always, the last step of any simplification is the same: build the truth table of the start and of the finish, and see them match.

## Say it to your companion

Tell your companion, in your own words: the laws let you rewrite an expression without changing its truth table — absorption swallows a term, a complement pair gives 1 or 0, and De Morgan's theorems say the bar over (A + B) is Ā · B̄ and the bar over (A · B) is Ā + B̄: break the bar, change the operation. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: state the commutative, associative, distributive, identity, null, complement, idempotent and absorption laws. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: prove a law by building the truth tables of both sides and showing the columns match. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: state De Morgan's two theorems and apply 'break the bar, change the operation' step by step. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: simplify a short Boolean expression using the laws, naming each law used, and verify the result with a truth table. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
