# LOGO conditionals — ifelse

## Do it first

Two numbers: 23 and 23. If they are equal, say YES — else say NO. Now: 23 and 25. Say it again. You have just run a conditional statement with your own voice. This lesson teaches LOGO's form of it.

## Conditional statements — deciding by a condition

**Conditional statements decide whether a condition is true or false**: the **if** part says what to do when the condition is **true**, and the **else** part what to do when it is **false**. **Leave out the else, and the application does nothing when the condition is false.**

The general form:

`ifelse [condition][action if true][action if false]`

[Picture 12317 — the road forks]

## The two worked examples

Both examples are written in the MSW LOGO editor and test the same condition — is `:variable1` equal to `:variable2`?

**Worked example 1.** Both variables are set to **23**. The test `:variable1 = :variable2` is true, and the program prints **"It's TRUE"**.

**Worked example 2.** The variables are set to **23 and 25**. The same test is false, and the program prints **"It's FALSE"** — the comment in the book means **variable2**, the second variable, where it speaks of the 25 (see sources).

## Say it to your companion

Tell your companion the general form of ifelse, the three parts, and what each worked example prints — and why.

## Do It Yourself

1. Write the general form of ifelse from memory, labelling its three parts.
2. Predict: variables 50 and 51 under the same test — what prints? (This is the unit's closing activity, first program.)
3. Write a conditional with no else part, and say exactly what happens when its condition is false.
