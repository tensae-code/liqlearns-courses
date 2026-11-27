# The Program Development Life Cycle

## Do it first

Think of one annoying repeated task — recording fees, marking a register, totalling market sales. Before imagining any code, answer three questions about it on paper: What goes in? What must come out? What are the limits and special cases? You have just done the two stages most beginners skip — the lesson names all the stages and shows why these come first.

## Sub lesson 1 — Before the code — recognising, defining and designing

Programs that fail usually fail before any code exists: they solve the wrong problem, or a fuzzy one. The **program development life cycle** therefore starts away from the keyboard. **Problem recognition** is noticing that a task — slow, repeated, error-prone — is a candidate for a program at all.

**Problem definition** pins the task down: exactly what the program must accept as **input**, exactly what it must produce as **output**, and the limits it must respect. This statement is agreed with the users, because they know the special cases (the pupil who pays in two instalments, the sale returned the next day) that a programmer alone would never guess.

**Program design** then plans the solution in a language-neutral form: an **algorithm** — the step-by-step method — written as **pseudocode** or drawn as a **flowchart**. Design errors are cheap here: moving a box on paper costs nothing; moving the same logic after a thousand lines of code costs days. Only a defined problem with a designed solution earns the right to be coded.

In your mind's eye: three panels: a teacher staring at a pile of fee receipts (recognition), a written card listing Inputs and Outputs (definition), and a flowchart of boxes and arrows (design).

[Picture 47862 — three panels: a teacher staring at a pile of fee receipts (recognition), a written card listing Inputs and Outputs (definition), and a flowchart of boxes and arrows (design)]

## Sub lesson 2 — Code, test, implement, maintain

**Coding** translates the design into a real programming language. Because the design already decided the logic, coding is translation, not invention — a well-designed program can even be coded by a different person, or in a different language, from the same flowchart.

**Testing** runs the program on prepared test data — normal, extreme and deliberately wrong values — to expose errors. **Debugging** is the hunt that follows: locating each exposed error and fixing it. The pair repeat until the tests pass. Errors come in kinds: **syntax** errors break the language's rules and stop translation; **logic** errors let the program run but produce wrong answers, and only testing catches them.

**Implementation** puts the finished program into real use: installing it, converting old data into its forms, and training the users. And the cycle does not end there — **maintenance** corrects faults found in use, improves the program, and adapts it when rules change (a new fee structure, a new tax). Maintenance is normally the longest and most expensive stage, which is why the cycle is drawn as a loop back to problem definition, not a line that ends. Kenya's Form 3 programming chapter teaches the cycle as the frame that holds its algorithm and flowchart work together.

In your mind's eye: a circular arrow diagram with seven stage labels around the ring, the maintenance label drawn widest.

[Picture 47863 — a circular arrow diagram with seven stage labels around the ring, the maintenance label drawn widest]

## Say it to your companion

Tell your companion, in your own words: Programs are built in a cycle of stages: recognise and define the problem, design the program (algorithm, pseudocode or flowchart), code it in a programming language, test and debug it, implement it for its users, and maintain it as needs change — and skipping the early stages is how programs end up solving the wrong problem perfectly. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the stages of the program development life cycle in order. Do this with a real example of your own, and write or say how you know it is right.
2. Show it, don't just say it: say what is produced at each stage (definition, design, code, test results, a working system, updates). Do this with a real example of your own, and write or say how you know it is right.
3. Show it, don't just say it: explain the difference between testing and debugging. Do this with a real example of your own, and write or say how you know it is right.
4. Show it, don't just say it: argue why problem definition comes before coding, using a concrete example. Do this with a real example of your own, and write or say how you know it is right.
