# Writing algorithms — add, decide, loop

## Do it first

Write, as numbered steps a computer could follow, how to add two numbers a person gives you. Keep your draft. This lesson models the method three times — add, decide, loop — and your draft meets the first model head-on.

## Model 1 — adding two numbers

In input/process/output steps:

1. **Take** the first number. *(input)*
2. **Take** the second number. *(input)*
3. **Add** the two numbers. *(process)*
4. **Display** the sum. *(output)*

Compare it with your draft: same steps, same order? That is the shape of every algorithm in this lesson.

[Picture 15722 — the three algorithms as step-cards]

## Model 2 — classifying a number (the first branching algorithm)

Enter a number, then decide:

1. **Take** the number. *(input)*
2. **If** the number is **below zero**, display **negative**. *(process — branch)*
3. **If** the number is **above zero**, display **positive**. *(process — branch)*
4. **Otherwise** display **zero**. *(process — branch)*

The output is one of three messages, chosen by the number itself — the book's first branching algorithm.

## Model 3 — summing ten numbers with a loop

The loop model, in the book's steps:

1. **sum** starts at **0**; counter **i** starts at **1**.
2. **Take** the i-th number. *(input)*
3. **Add** it to the sum. *(process)*
4. **Increase i by 1**.
5. **Check** whether i is still under the limit — the book's printed check reads **“less than 10”** — and **loop back** to step 2, or finish.
6. **Output** the sum. *(output)*

Watch the counter in the GIF: i ticks upward, the sum grows each turn, and the check is what stops the loop.

[GIF 15723 — the counter i ticking while the sum grows]

## Say it to your companion

Talk your companion through model 3 turn by turn: say i and the sum aloud for the first three turns, and name the step that sends you back.

## Do It Yourself

1. Write the algorithm: read a number and display double the number. Mark input, process, output.
2. Write the classifying algorithm for temperature: below 0 'freezing', above 0 'not freezing' — then say why zero needs care.
3. Trace model 3 on paper for the numbers 1, 2, 3 only: write sum and i after every step.
