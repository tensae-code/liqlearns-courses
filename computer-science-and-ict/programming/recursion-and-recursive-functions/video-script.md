# Video script — Recursion and Recursive Functions in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **recursive function** solves a problem by calling **itself on a smaller piece** of it. Every working recursion has two parts: the **base case** — the smallest piece, answered directly, where the calls stop — and the **recursive case** — the answer for the whole built from the answer for the smaller piece. Factorial is the book's standing example: n! = n × (n−1)!, with 0! = 1 as the base — the definition and the program have the same shape, which is recursion's beauty and its danger.
Each call **waits** on the call-stack for its smaller call's answer; when the base case answers, the stack **unwinds**, each waiting call completing in turn. The faults are the two missing guards: **no base case** (or one never reached) — calls without end, until Python stops the program with a recursion error; and a recursive step that does not **shrink** the problem — the same endlessness by another road. Jordan teaches recursion after the data structures because its finest work is on them: trees and nested lists are smaller-piece-shaped by nature.
