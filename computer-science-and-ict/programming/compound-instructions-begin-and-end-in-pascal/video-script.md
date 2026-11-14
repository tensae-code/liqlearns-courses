# Video script — Compound Instructions — begin and end in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **compound instruction** is a sequence of instructions enclosed by **begin** and **end**, treated by the grammar as **one instruction**. The instructions inside are separated by semicolons — none is needed after the last, before end (a semicolon there only adds an empty instruction). C++ wraps the same idea in **braces { }**. Wherever the grammar asks for one instruction — an if's branch, a loop's body, a case's label — a compound instruction can stand, carrying as many steps as the work needs.
Without the wrapper, governance leaks: in `if x > 0 then a := 1; b := 2;` only a := 1 is conditional — b := 2 runs always, because the if governs one instruction. With begin…end around both, the pair stands or falls together. The lesson's reading habit follows: to know what any governing instruction commands, find its **one instruction** — a single step, or the whole begin…end block — and draw its border before judging the program. Most beginner logic errors are border errors.
