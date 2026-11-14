# Video script — The Repeat-Until Instruction in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **repeat** instruction reads `repeat <instructions> until <condition>`: the body runs, **then** the condition is tested — if it is **false**, the body repeats; if **true**, the loop ends. Two gifts follow from the order. The body is a bare sequence — **no begin…end needed**, repeat and until are themselves the brackets. And the body runs **at least once**, always: a repeat loop can never be skipped, which is exactly right for work like 'ask until the answer is valid'.
Set the loops side by side: **while** tests first and repeats while its condition is **true** — it may run zero times; **repeat** tests last and repeats until its condition is **true** — it runs at least once, and its ending condition is the while's negation (repeat until x = 0 is while x <> 0 continued). C++ writes the same loop **do…while**. Choosing is a question about the first run: must the body act before any test makes sense — reading a value, showing a menu? Then repeat; must the test guard even the first entry? Then while.
