# Loops in flowcharts — initialise, compute, test, increment

## Do it first

A flowchart flows downward, box to box. But summing the first 50 numbers means doing the same step 50 times. How could a chart go *back* — and what stops it going back forever? Sketch your idea. Then read the four parts every loop is built from, and check your sketch against them.

## The four parts of a loop

Where statements must repeat until a condition is satisfied, the loop is built from four parts:

1. **Initialisation** — the variables and the exit counter are set before the loop starts.
2. **Computation** — the processing done on each turn.
3. **Test** — the way out; without it, the program would loop endlessly.
4. **Increment** — the counter is reset (increased) ready for the next turn.

[Picture 15727 — the sum-to-50 flowchart's four parts]

## The worked problem — sum of the first 50 natural numbers

The algorithm first, in words:

1. **Initialise** sum to **0** and counter to **1**.
2. **While** the counter is **at most 50**: **add** the counter to the sum *(computation)*, **increase** the counter by 1 *(increment)*, and repeat.
3. Otherwise **exit** the loop *(the test)*.
4. **Write** the sum.

Drawn as a flowchart, the **decision block** sends the flow **back round** until the counter reaches 50 — then the flow leaves the loop, and the final sum is displayed through the **output symbol**. Follow the marker in the GIF: counter rising, sum growing, then the exit.

[GIF 15728 — the flow marker circling the loop until the counter reaches 50]

## Say it to your companion

Name the four parts to your companion, then point at the sum-to-50 chart and say which part each block is doing.

## Do It Yourself

1. Draw the sum-to-50 flowchart on paper, and colour the four parts in four colours.
2. A loop has no test. Say exactly what goes wrong, and which algorithm characteristic it breaks.
3. Change the worked problem: sum of the first 20 numbers. What single number in the chart changes?
