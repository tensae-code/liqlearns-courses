# Video script — Frequently Used Logical Functions

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**NAND** is **NOT-AND**: it gives 0 only when both inputs are 1 — the exact negation of AND's table. **NOR** is **NOT-OR**: it gives 1 only when both inputs are 0. Each is **universal**: NAND alone (or NOR alone) can build NOT, AND and OR — whole circuits from one gate kind, which is why real chips are so often NAND chips. Their tables are written by the section's method: take the base function's table, and flip every output.
**XOR (exclusive or)** gives 1 when the inputs **differ** (0⊕1, 1⊕0) and 0 when they agree — the function of difference, which is why it is addition's heart: a sum bit is XOR of the addends, carry aside. **XNOR** is its negation — 1 when the inputs **agree** — the function of sameness, used wherever equality of bits is tested. With these four the chapter's kit is complete: every logical function a school circuit will need is basic, negated or comparative — all provable in four-row tables.
