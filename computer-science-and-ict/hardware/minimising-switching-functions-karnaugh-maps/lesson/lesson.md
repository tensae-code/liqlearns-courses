# Minimising Switching Functions — Karnaugh Maps

## Do it first

Here is a switching function as first written down: Y = Ā·B·C + A·B·C + Ā·B·C̄ + A·B·C̄ — four terms, eleven gate inputs' worth of hardware. Yet its truth table has 1s in only one tidy block, and the whole function is really just Y = B. A builder who wires the first form wastes gates, money and power on every single copy of the circuit. Minimising a switching function means finding the smallest expression with the same truth table. Montenegro's book teaches two methods — algebra and the Karnaugh map — and this lesson teaches both.

## Sub lesson 1 — Why minimise, and the algebraic method

A **switching function** is a Boolean expression that tells a circuit when to switch its output to 1. The first form you write down for one is almost never the smallest: it comes from reading the truth table row by row, one long term per row of 1s. **Minimising** means finding the smallest expression with the same truth table — and smallest is measured in gates and gate-inputs, because every gate is a real component that costs money, space and power, in every copy of the circuit ever built.

The **algebraic method** is the laws lesson put to work, with one golden pattern on top of them: **two terms that are identical except that one variable appears plain in one and barred in the other merge into one shorter term** — because A·X + A·X̄ can be factored to A·(X + X̄) = A·1 = A. Watch it eat the opening example: Ā·B·C + A·B·C share everything except A, so they merge to B·C. The other pair, Ā·B·C̄ + A·B·C̄, merges to B·C̄. Now B·C + B·C̄ merge the same way over C, leaving **Y = B**. Four terms became one letter — and the truth table never changed.

[Picture — the four-term expression shrinking in three steps, each merging pair bracketed and the law written under each step]

The algebraic method is exact, but it depends on *spotting* the pairs, and in a long expression the eye misses them. That is why the book teaches a second method that turns spotting into looking — the map.

## Sub lesson 2 — Karnaugh maps — minimising by eye

The **Karnaugh map** (say 'kar-naw') is the truth table folded into a grid so that *neighbours differ in exactly one variable* — the merging pattern from the algebraic method, made visible. To make neighbours behave that way, the rows and columns are **not** labelled 00, 01, 10, 11. They are labelled in **Gray-code order: 00, 01, 11, 10**, where each step changes only one bit. The map also **wraps around**: the left edge neighbours the right edge, and the top neighbours the bottom, because those cells differ in one variable too.

Working the map is four steps. (1) Draw the grid for your number of variables — two variables make 2×2, three make 2×4, four make 4×4. (2) Copy each 1 from the truth table into its cell. (3) Cover the 1s with rectangles of size **1, 2, 4 or 8** — never 3, never 6 — making each rectangle as large as you can, overlapping where it helps, until every 1 is inside a big rectangle. (4) Read one term per rectangle: a variable that is 1 all through the rectangle stays plain, a variable that is 0 all through stays barred, and a variable that *changes* inside the rectangle is dropped — it has been merged away.

[Picture — a four-variable Karnaugh map with Gray-code labels 00, 01, 11, 10 on both axes, its 1s covered by two large rectangles, one of them wrapping around the left and right edges]

Take the opening example onto a three-variable map: the four 1s fill the whole B = 1 half of the grid — one rectangle of four — inside which B is always 1 while A and C both change and drop out. The map reads **Y = B** at a glance, the answer the algebra reached in three steps. Bigger rectangles mean more variables dropped, which is why 'as large as possible' is the rule: a group of 2 drops one variable, a group of 4 drops two, a group of 8 drops three. When the map and a truth-table check agree, the minimised function is proved.

## Say it to your companion

Tell your companion, in your own words: minimising finds the smallest expression with the same truth table; algebraically, terms differing in one variable merge; on a Karnaugh map the truth table is drawn in Gray-code order so neighbouring 1s group into rectangles of 1, 2, 4 or 8, and each rectangle reads off as one term with the changing variables dropped. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a switching function is and why minimising it saves real hardware. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: merge pairs of terms that differ in exactly one variable, using distribution and the complement law. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: draw a Karnaugh map for two, three or four variables with Gray-code order 00, 01, 11, 10, including the wrap-around edges. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: group the 1s in rectangles of 1, 2, 4 or 8 and read the minimised expression off the groups. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
