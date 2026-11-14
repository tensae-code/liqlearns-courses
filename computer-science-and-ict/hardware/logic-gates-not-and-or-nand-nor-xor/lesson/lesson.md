# Logic Gates — NOT, AND, OR, NAND, NOR, XOR

## Do it first

In the Boolean lessons the operations lived on paper as truth tables. A **logic gate** is that same operation made physical: a small electronic circuit with input pins and one output pin. Put 0s and 1s on the inputs — as low and high voltages — and the output settles to the operation's answer almost instantly. Wire gates together and the combined circuit computes a whole switching function. Every processor, memory chip and controller in every computer is gates, all the way down. This lesson goes through the book's family in order: the basic gates, the combined gates, and the complex gates built from several.

## Sub lesson 1 — The basic gates — inverter, AND, OR

Three gates carry the three basic operations, and each is known by three writings that must agree: its **symbol**, its **expression**, and its **truth table**.

The **inverter**, or NOT gate, has one input and one output. Its symbol is a triangle pointing the way the signal flows, with a small circle — the bubble — at the tip; the bubble is the mark of negation wherever it appears in this subject. Expression: Y = Ā. Table: 0 in gives 1 out, 1 in gives 0 out.

The **AND gate** has two or more inputs and one output, drawn as a flat-backed shape with a rounded front. Expression: Y = A · B. The output is 1 only on the all-ones row of the table — 'all or nothing', exactly the AND you already know.

The **OR gate** is drawn with a curved back and a pointed front. Expression: Y = A + B. The output is 1 on every row except all-zeros — 'at least one', exactly the OR you already know.

[Picture — the three basic gates in a row, each with its symbol, its expression under it, and its truth table beside it, the inverter's bubble circled]

Nothing here is new behaviour — the gates *are* the operations. What is new is thinking of them as things with pins: a gate takes the voltages that arrive now and answers now, with no memory of what came before. Circuits with memory come later in the climb, and they are built by wiring these forgetful gates in a loop.

## Sub lesson 2 — NAND, NOR, XOR, XNOR — and complex gates

Add an inverter to the output of AND and you get **NAND** — 'not-AND'. Its symbol is the AND shape with a bubble at the tip, its expression is the bar over (A·B), and its table is the AND table flipped: the output is 0 only on the all-ones row, 1 everywhere else. **NOR** is the same move on OR: output 1 only on the all-zeros row, 0 everywhere else. De Morgan's theorems from the earlier lesson tell you what these gates secretly are: a NAND with its output read one way is an OR of negated inputs, which is the first hint of their superpower.

**XOR** has a symbol like OR with an extra curve at the back; its output is 1 when the inputs are different. **XNOR** is XOR with the bubble: output 1 when the inputs are the *same* — an equality checker in one component.

[Picture — NAND, NOR, XOR and XNOR in a row with their symbols and tables, the bubbles that mark negation picked out in colour]

The superpower: **NAND is a universal gate, and so is NOR.** Tie a NAND's inputs together and it is an inverter. Follow a NAND with that inverter and you have AND. Negate the inputs of a NAND and De Morgan turns it into OR. So NOT, AND and OR — and therefore *every* switching function — can be built from NANDs alone, and chip makers do exactly that: one gate type, made by the million, wired in patterns. The gates lesson of any real factory is mostly NAND.

Finally, **complex gates** pack a whole small expression into one component: the AND-OR-INVERT gate, for example, ANDs two pairs of inputs, ORs the results and inverts the output — Y = the bar over (A·B + C·D) — drawn as AND shapes feeding an OR shape with a bubble. Read a complex gate the way you read an expression: stage by stage, from inputs to output.

## Say it to your companion

Tell your companion, in your own words: a gate is a Boolean operation made physical; NOT, AND and OR are the basic gates; NAND and NOR are AND and OR with an inverter on the output, and each of them alone can build every other gate; XOR answers 'different', XNOR answers 'same'; and complex gates pack a whole expression into one component. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: draw the symbols and write the expressions of the inverter, AND and OR gates, and give any gate's output for given inputs. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: state the truth behaviour of NAND, NOR, XOR and XNOR in one sentence each. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: show how NAND alone builds NOT, AND and OR (and say the same is true of NOR), using De Morgan. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: read a complex gate such as AND-OR-INVERT and write its Boolean expression. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
