# Evaluating Expressions — and Operator Precedence in Pascal

## Do it first

An expression is a question the program asks its data. Two Moldova books give the evaluation its own section, because every later instruction — assignment, condition, loop — spends expressions whose worth must be known exactly.

## Sub lesson 1 — The parts of an expression — operands and operators

An **expression** is built from **operands** (the values: constants, variables, function results) joined by **operators** (the operations: +, −, *, /, div, mod and the rest). Evaluating it means **working it out to one value**. The parts are read as in algebra, but written flat, in one line: a fraction's numerator and denominator must be bracketed — (a + b) / (c − d) — because the line has no floors. A **standard function call** like sqrt(x) is an operand: it is evaluated to its value wherever it stands.

[Picture — The parts of an expression — operands and operators]

## Sub lesson 2 — Precedence — the order of working out

Operators bind with different strength — **precedence**. The order of evaluation: **brackets first**; then the multiplication family (**, /, div, mod, and*)**; then the addition family (**, −, or*)**; operators of equal strength work **left to right**. So 2 + 3 * 4 is 14, not 20, and (2 + 3) * 4 is 20 because brackets outrank all. Relations (=, <, >…) bind weakest of all, comparing finished values. The professional's rule rides with it: when the reader could hesitate, **bracket** — precedence is for the machine, clarity is for people.

[Picture — Precedence — the order of working out]

## Say it to your companion

Tell your companion, in your own words: An **expression** is built from **operands** (the values: constants, variables, function results) joined by **operators** (the operations: +, −, *, /, div, mod and the rest). Evaluating it means **working it out to one value**. The parts are read as in algebra, but written flat, in one line: a fraction's numerator and denominator must be bracketed — (a + b) / (c − d) — because the line has no floors. A **standard function call** like sqrt(x) is an operand: it is evaluated to its value wherever it stands. Operators bind with different strength — **precedence**. The order of evaluation: **brackets first**; then the multiplication family (**, /, div, mod, and*)**; then the addition family (**, −, or*)**; operators of equal strength work **left to right**. So 2 + 3 * 4 is 14, not 20, and (2 + 3) * 4 is 20 because brackets outrank all. Relations (=, <, >…) bind weakest of all, comparing finished values. The professional's rule rides with it: when the reader could hesitate, **bracket** — precedence is for the machine, clarity is for people. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Operands (values) joined by operators (operations). Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Working it out to one value. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Pascal expressions are written flat in one line — the line has no floors. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: An operand — evaluated to its value where it stands. Do this with a real example of your own and write or say how you know it is right.
