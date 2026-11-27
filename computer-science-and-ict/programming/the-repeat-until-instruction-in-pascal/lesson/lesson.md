# The Repeat-Until Instruction in Pascal

## Do it first

Two loops test before; this one tests after. Grade 8 closes its Pascal instructions, and Grade 10 its dual-language set, with repeat…until — the loop that guarantees its body at least one full run.

## Sub lesson 1 — Body first, test after

The **repeat** instruction reads `repeat <instructions> until <condition>`: the body runs, **then** the condition is tested — if it is **false**, the body repeats; if **true**, the loop ends. Two gifts follow from the order. The body is a bare sequence — **no begin…end needed**, repeat and until are themselves the brackets. And the body runs **at least once**, always: a repeat loop can never be skipped, which is exactly right for work like 'ask until the answer is valid'.

In your mind's eye: body first, test after.

[Picture 47872 — body first, test after]

## Sub lesson 2 — repeat against while — and do-while

Set the loops side by side: **while** tests first and repeats while its condition is **true** — it may run zero times; **repeat** tests last and repeats until its condition is **true** — it runs at least once, and its ending condition is the while's negation (repeat until x = 0 is while x <> 0 continued). C++ writes the same loop **do…while**. Choosing is a question about the first run: must the body act before any test makes sense — reading a value, showing a menu? Then repeat; must the test guard even the first entry? Then while.

In your mind's eye: repeat against while — and do-while.

[Picture 47873 — repeat against while — and do-while]

## Say it to your companion

Tell your companion, in your own words: The **repeat** instruction reads `repeat <instructions> until <condition>`: the body runs, **then** the condition is tested — if it is **false**, the body repeats; if **true**, the loop ends. Two gifts follow from the order. The body is a bare sequence — **no begin…end needed**, repeat and until are themselves the brackets. And the body runs **at least once**, always: a repeat loop can never be skipped, which is exactly right for work like 'ask until the answer is valid'. Set the loops side by side: **while** tests first and repeats while its condition is **true** — it may run zero times; **repeat** tests last and repeats until its condition is **true** — it runs at least once, and its ending condition is the while's negation (repeat until x = 0 is while x <> 0 continued). C++ writes the same loop **do…while**. Choosing is a question about the first run: must the body act before any test makes sense — reading a value, showing a menu? Then repeat; must the test guard even the first entry? Then while. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: repeat <instructions> until <condition>. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: After the body runs. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: On true — it repeats while the condition is false. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — repeat and until are themselves the brackets. Do this with a real example of your own and write or say how you know it is right.
