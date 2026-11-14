# Boolean Algebra and Logic Operations

## Do it first

Think of a hall light with two switches. In one hall the light is on only when both switches are on. In another hall, either switch alone is enough to light it. On a staircase, flipping either switch changes the light — on becomes off, off becomes on. Three behaviours, all built from just 'on' and 'off'. Boolean algebra is the small, exact mathematics of those two states, and this lesson teaches its operations: NOT, AND, OR and XOR. Every decision a computer chip ever makes is built from these.

## Sub lesson 1 — The two values and the three basic operations — NOT, OR, AND

Boolean algebra — named after George Boole — is algebra where a variable can hold only two values: **0 and 1**, which we also read as false and true, off and on. There is no 2, no half, no maybe. That restriction is exactly why it fits a computer, whose bits are 0 and 1 and nothing else.

Three operations are basic; everything else is built from them.

**Negation — NOT.** Written with a bar: Ā (read 'not A'). It flips the value: NOT 0 = 1, NOT 1 = 0. One input, two rows in its truth table — the smallest operation there is.

**Logical addition — OR.** Written A + B (read 'A or B'). It gives 1 when **at least one** input is 1: 0+0 = 0, 0+1 = 1, 1+0 = 1, 1+1 = 1. Here 'addition' is only a name — 1 + 1 = 1, not 2, because 2 does not exist in this algebra.

**Logical multiplication — AND.** Written A · B (read 'A and B'). It gives 1 only when **all** inputs are 1: 0·0 = 0, 0·1 = 0, 1·0 = 0, 1·1 = 1. Hold the two sayings apart: OR is 'at least one', AND is 'all'. Almost every beginner's mistake in this subject is swapping those two sayings.

[Picture — the three truth tables of NOT, OR and AND drawn as one chart, with the output column of OR shaded where at least one input is 1 and the output column of AND shaded only on the all-ones row]

A **truth table** lists every possible input combination in order — for two inputs the four rows 00, 01, 10, 11 — and the output for each. A truth table is not an example of an operation; it *is* the operation, complete. Two expressions with the same truth table do exactly the same job, whatever they look like — remember that; a later lesson uses it to simplify circuits.

## Sub lesson 2 — Exclusive OR, and reading combined expressions

The staircase light from the opening has its own operation. **Exclusive OR — XOR**, written A ⊕ B, gives 1 when the two inputs are **different**: 0⊕0 = 0, 0⊕1 = 1, 1⊕0 = 1, 1⊕1 = 0. Read it as 'one or the other, but not both'. Flip either staircase switch and the light changes; flip both and you are back where you started — that is XOR in the walls of a house. XOR also earns its keep inside arithmetic, where 'different bits give 1, same bits give 0' turns out to be exactly what adding two bits does before any carry is thought about.

Real expressions combine operations: Y = A · B̄ + C. Work them the way you work arithmetic — brackets first, then NOT, then AND, then OR. To build the truth table of a combined expression, give each operation its own column: first the eight rows of A, B, C (three inputs make 2³ = 8 rows); then a column for B̄; then a column for A · B̄, multiplying row by row; then the last column adds C with OR. Column by column, no step is ever hard — the whole skill is refusing to do two steps in one jump.

[Picture — the truth table of Y = A·B̄ + C being built in stages, with a new column appearing for each operation and the working columns in a lighter shade]

Count the rows before you start: n inputs always make 2ⁿ rows. Two inputs, 4 rows; three inputs, 8 rows; four inputs, 16 rows. If your table has the wrong number of rows, it is wrong before a single output is written.

## Say it to your companion

Tell your companion, in your own words: Boolean algebra works with 0 and 1 only; NOT flips a value; OR gives 1 when at least one input is 1; AND gives 1 only when all inputs are 1; XOR gives 1 when the inputs are different; and a truth table with n inputs has 2ⁿ rows. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a Boolean variable is and write the truth tables of NOT, OR and AND from memory. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: write the truth table of XOR and say how it differs from OR in one row only. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: count the rows of any truth table as 2ⁿ for n inputs. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: build the truth table of a combined expression column by column, in the order: brackets, NOT, AND, OR. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
