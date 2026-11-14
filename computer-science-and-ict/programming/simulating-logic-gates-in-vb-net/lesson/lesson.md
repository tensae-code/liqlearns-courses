# Simulating Logic Gates in VB.NET

## Do it first

Egypt's Grade 12 programming project takes each logic gate three times: the gate itself, then a simulation program of it in Visual Basic .NET, then the same in PHP. This lesson is the VB.NET telling — one project per gate, rebuilt as the gates change, so the pupil's program grows exactly as their logic does.

## Sub lesson 1 — The simulation idea — inputs in, lamp out

A **gate simulation** is a small program that behaves as the gate behaves: the user sets the **inputs** (switches, check boxes, buttons — 0s and 1s made clickable), the program applies the gate's **logic**, and an **output** — a lamp, a label, a colour — shows the result. Building it in **VB.NET** means building a form: controls placed for the two inputs and the output, and code behind the controls that recomputes the output whenever an input changes. The simulation's teaching power is its honesty: set the inputs to every row of the gate's truth table and the program must agree with the table every time — the table becomes a test the program can fail.

[Picture — The simulation idea — inputs in, lamp out]

## Sub lesson 2 — AND, then OR, then NOT — one project, three logics

Egypt builds the project **three times**, once per gate, and the repetition is the method. For **AND**, the output code demands both inputs; for **OR**, either suffices; for **NOT**, the single input is inverted. Everything else — the form, the switches, the lamp, the event code that refreshes the output — stays the same, so the pupil sees the **one line that is the gate** standing out from the machinery around it. By the third build the pattern is owned: a new gate would need a new line and nothing else. The project then mirrors the whole thing in PHP — the same logic wearing a web page — and closes by spending the gates on life decisions.

[Picture — AND, then OR, then NOT — one project, three logics]

## Say it to your companion

Tell your companion, in your own words: A **gate simulation** is a small program that behaves as the gate behaves: the user sets the **inputs** (switches, check boxes, buttons — 0s and 1s made clickable), the program applies the gate's **logic**, and an **output** — a lamp, a label, a colour — shows the result. Building it in **VB.NET** means building a form: controls placed for the two inputs and the output, and code behind the controls that recomputes the output whenever an input changes. The simulation's teaching power is its honesty: set the inputs to every row of the gate's truth table and the program must agree with the table every time — the table becomes a test the program can fail. Egypt builds the project **three times**, once per gate, and the repetition is the method. For **AND**, the output code demands both inputs; for **OR**, either suffices; for **NOT**, the single input is inverted. Everything else — the form, the switches, the lamp, the event code that refreshes the output — stays the same, so the pupil sees the **one line that is the gate** standing out from the machinery around it. By the third build the pattern is owned: a new gate would need a new line and nothing else. The project then mirrors the whole thing in PHP — the same logic wearing a web page — and closes by spending the gates on life decisions. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A small program that behaves as the gate behaves — inputs set, logic applied, output shown. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Inputs as switches or similar controls; the output as a lamp, label or colour. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: Only the gate's logic — the form, switches, lamp and refresh machinery stay the same. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: The output is on only when both inputs are on. Do this with a real example of your own and write or say how you know it is right.
