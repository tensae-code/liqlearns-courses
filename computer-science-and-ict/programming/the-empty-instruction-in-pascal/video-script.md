# Video script — The Empty Instruction in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **empty instruction** is the **absence of an instruction where one is grammatically allowed**: between two semicolons (`;;`), after begin, or before end. It **does nothing** — no action, no state change — and it is legal everywhere an instruction may stand. Its honest uses are rare: a loop whose work is all in its condition, a placeholder kept while building. Pascal's grammar treats the semicolon as a **separator** between instructions, not a terminator — which is exactly why an empty instruction can slip in unnoticed.
The empty instruction's famous crime: `if x > 0 then ; writeln(x)` — the semicolon after then makes the if's body the **empty instruction**, so writeln runs **always**, not conditionally; and `while not eof do ;` hangs forever, its body empty, its condition never changed by nothing. The defence is reading: a semicolon before a body that matters should ring a bell. What the machine executes is what is written — an empty body is executed, obediently, a million times a second.
