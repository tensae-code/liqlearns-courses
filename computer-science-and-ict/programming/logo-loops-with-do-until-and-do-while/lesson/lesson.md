# LOGO loops with do.until and do.while — predicting outputs

## Do it first

From the last lesson you know: `until [condition][action]`. Here is a new form: `do.until [action][condition]`. Before any explanation — what do you think swapped, and would a counting loop still print the same numbers? Write your prediction. This lesson is the unit's predicting lesson: every answer is earned before it is run.

## do.until and do.while — the order swapped

**do.until and do.while are effectively the same as until and while, except that the action and the condition are reversed:**

- `do.until [action][condition]`
- `do.while [action][condition]`

[Picture 12320 — order swapped]

## The worked examples

The worked examples count with **print-and-increment** actions:

- **do.until** prints **1 up to 10**, before the count passes 10.
- **do.while** prints **1 to 9**, while the count stays below 10.

Same start, same step — the guard decides the last number, as in the last lesson.

## The closing activity — predict all four

The unit closes by asking for the outputs of four given programs. Predict each before you run it:

1. **An ifelse test on 50 and 51** — the equality test is false; it prints **"It's FALSE"**.
2. **An until loop stepping by 2 from 12** — it prints **12 14 16 18 20**.
3. **A do.until loop stepping by 5 from 1** — it prints **1 6 11** before the count carries it past the guard.
4. **A SQUARE procedure repeated 20 times with a turn** — it draws a **ring of squares**.

[GIF 12321 — a ring of squares]

## Say it to your companion

Tell your companion what swapped in the do forms, both counting outputs, and the four predicted outputs with their reasons.

## Do It Yourself

1. Write both do forms from memory, with the part order labelled.
2. Run all four closing programs in MSW LOGO and mark your predictions from the lesson.
3. Change the do.while guard so it prints 1 to 10. What condition does that take — and why?
