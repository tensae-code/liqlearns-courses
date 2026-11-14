# Video script — Building a Calculator Programme

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Before code, the **design**: the programme **asks for two numbers and an operation**, **computes** by the operation chosen, and **prints the result** — input, process, output, the shape of the simple-program lesson, grown to a tool. The design decisions are the programmer's own: ask the operation as a word or a symbol? What happens if the operation is unknown, or the second number is zero and the operation is division? A calculator that answers wrongly with confidence is worse than one that refuses honestly — the design must say what refusal looks like.
The build hangs on **selection**: an if-elif-else chain reads the operation and sends the numbers to the matching arithmetic — the chain of choices lesson, employed. Each branch computes and the programme prints from one place, so the output's form is written once. The book's session tests the calculator as a team tool is tested: known answers first (2 + 3 must be 5), then the edges — division by zero, a mistyped operation, enormous numbers — and the programme is only finished when the edges behave as the design promised. Pieces, assembled, tested: that is a programme.
