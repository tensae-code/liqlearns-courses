# Video script — Iterative or Recursive — Choosing the Approach

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **iterative** solution drives its work with a **loop and explicit variables**: the programmer keeps the state, step by visible step. A **recursive** solution lets a subprogram **call itself** on a smaller part, the state kept implicitly in the **chain of calls** — each call's own variables waiting on the stack until its inner call returns. The recursion reads as the problem's own definition (factorial, tree walks, divide-and-conquer); the iteration shows its machinery. Same answers — different bookkeeping.
Recursion pays in **memory**: every pending call holds a stack frame, so a recursion as deep as its input (a million-deep factorial) can **overflow the stack**, while iteration's variables are a fixed few. Recursion often pays also in repeated work when subcalls overlap (the naive Fibonacci computes the same values exponentially often) — unless its structure is a true division with no overlap. The chapter's rule: **recurse where the problem is self-similar and division is clean and depth is modest; iterate where depth is huge, overlap would repeat work, or the loop is simply plain**. Judge by the structure, not by fashion.
