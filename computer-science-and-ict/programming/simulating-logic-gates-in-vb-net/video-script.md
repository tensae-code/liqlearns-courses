# Video script — Simulating Logic Gates in VB.NET

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **gate simulation** is a small program that behaves as the gate behaves: the user sets the **inputs** (switches, check boxes, buttons — 0s and 1s made clickable), the program applies the gate's **logic**, and an **output** — a lamp, a label, a colour — shows the result. Building it in **VB.NET** means building a form: controls placed for the two inputs and the output, and code behind the controls that recomputes the output whenever an input changes. The simulation's teaching power is its honesty: set the inputs to every row of the gate's truth table and the program must agree with the table every time — the table becomes a test the program can fail.
Egypt builds the project **three times**, once per gate, and the repetition is the method. For **AND**, the output code demands both inputs; for **OR**, either suffices; for **NOT**, the single input is inverted. Everything else — the form, the switches, the lamp, the event code that refreshes the output — stays the same, so the pupil sees the **one line that is the gate** standing out from the machinery around it. By the third build the pattern is owned: a new gate would need a new line and nothing else. The project then mirrors the whole thing in PHP — the same logic wearing a web page — and closes by spending the gates on life decisions.
