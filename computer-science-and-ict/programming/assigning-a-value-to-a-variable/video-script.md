# Video script — Assigning a Value to a Variable

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In **x = expression;** the machine **evaluates the right side completely**, then **copies the result into x**, destroying x's previous value. `int x;` alone leaves x holding garbage until an assignment (or input) gives it a real value — a variable's **initialisation** is simply its first assignment, often written with the declaration: `int x = 0;`.
Because = means store, **x = x + 1** reads: take x's current value, add 1, store it back — the standard **counter** step, impossible as an equation and ordinary as an instruction. Chained thinking follows: swap two variables needs a **third** to hold one value during the exchange, because the first store destroys what the second still needs.
