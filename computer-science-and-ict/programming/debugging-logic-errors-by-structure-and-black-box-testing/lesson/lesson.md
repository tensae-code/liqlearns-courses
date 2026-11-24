# Debugging Logic Errors by Structure — and Black-Box Testing

## Do it first

A logic error does not announce itself; the program runs and lies politely. Greece's supplementary unit teaches the hunt as a craft: search structure by structure, and test from outside without trusting the code's own story.

## Sub lesson 1 — Where logic errors hide — structure by structure

The unit sorts the hunt by the structure under suspicion. In **selection**: the condition's edges (what happens *at* the boundary value?) and the branch that was never taken in testing. In **repetition**: the loop that runs once too few or too many, and the variable never updated inside it. In **arrays**: the index that steps one place too far, the loop bound that skips the last place. In **subprograms**: the parameter passed in the wrong order, the local name shadowing the caller's. Each structure has its own favourite hiding places, and the debugger checks them in that structure's order.

In your mind's eye: where logic errors hide — structure by structure.

## Sub lesson 2 — Black-box testing — judging from outside

**Black-box testing (μαύρο κουτί)** tests the program **from its statement alone**: the tester chooses inputs — typical, boundary and hostile — computes the **expected** answers by hand from what the program *should* do, runs it, and compares, never reading the code and so never excused by it. A mismatch convicts the program, not the test. Beside the error-kind teaching of the same unit (syntactic errors, abnormal-termination errors, logic errors), black-box testing is the standing method: it finds logic errors precisely because it refuses to be told where to look kindly.

In your mind's eye: black-box testing — judging from outside.

## Say it to your companion

Tell your companion, in your own words: The unit sorts the hunt by the structure under suspicion. In **selection**: the condition's edges (what happens *at* the boundary value?) and the branch that was never taken in testing. In **repetition**: the loop that runs once too few or too many, and the variable never updated inside it. In **arrays**: the index that steps one place too far, the loop bound that skips the last place. In **subprograms**: the parameter passed in the wrong order, the local name shadowing the caller's. Each structure has its own favourite hiding places, and the debugger checks them in that structure's order. **Black-box testing (μαύρο κουτί)** tests the program **from its statement alone**: the tester chooses inputs — typical, boundary and hostile — computes the **expected** answers by hand from what the program *should* do, runs it, and compares, never reading the code and so never excused by it. A mismatch convicts the program, not the test. Beside the error-kind teaching of the same unit (syntactic errors, abnormal-termination errors, logic errors), black-box testing is the standing method: it finds logic errors precisely because it refuses to be told where to look kindly. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: By structure — selection, repetition, arrays, subprograms. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The condition's edges and the branch never taken in testing. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A loop running once too few or too many (or a variable never updated inside it). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: An index one place too far (or a bound skipping the last place). Do this with a real example of your own and write or say how you know it is right.
