# LOGO loops with until and while

## Do it first

Count aloud from 1. Add one each time. Stop exactly when your count passes 5. Say the rule that stopped you, in one sentence. You have just obeyed a condition over and over — this lesson gives that obedience its two LOGO forms.

## until and while — loops under a condition

`until [condition][action]` and `while [condition][action]` **repeat an action under a condition**. The difference is in the guard: **until** repeats **until the condition becomes true**; **while** repeats **while the condition stays true**.

## The until example — counting from 1

The book's until example counts from 1:

```
make "count 1
until [:count > 5][print :count make "count :count + 1]
```

Round by round: print the count, then add 1 — until the count is **greater than 5**. The output is:

**1 2 3 4 5**

[Picture 12318 — until, the guarded loop]

[GIF 12319 — 1 2 3 4 5, then stop]

## The while example — counting from 5

The book's while example starts the count at **5** and prints while the count is **below 10**: `while [:count < 10][print :count make "count :count + 1]`. Follow the condition honestly: 5 prints, 6, 7, 8, **9 prints** — then the count becomes 10, `count < 10` is **false**, and the loop stops. The true output is **5 6 7 8 9** — 10 is never printed, because the condition must be true *before* the round runs. (The book says the example outputs 5–10; the lesson follows the condition, and the book's claim is flagged in the sources.)

## Say it to your companion

Tell your companion the two loop forms, how their guards differ, both examples, and why the while output ends at 9.

## Do It Yourself

1. Write the until program from memory and its output.
2. Trace the while example in a table: count before, printed, count after — every round to the stop.
3. Predict, then run in MSW LOGO: the until example with the guard changed to :count > 3. What prints?
