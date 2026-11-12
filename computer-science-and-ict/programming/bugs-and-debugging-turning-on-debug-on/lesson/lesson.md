# Bugs and debugging — turning on [DEBUG ON]

## Do it first

Write a divide program, save it, and run it with the second number 0. It crashes. The crash was not visible when you READ the code — it appeared when you RAN it. Finding that kind of hidden fault is **debugging**, and IDLE has a tool built for it. By the end of this lesson your shell will carry three new words before its prompt: **[DEBUG ON]**.

## Sub lesson 1 — Test first — run it and compare with the expected output

After writing and saving a program, you **run it to test** whether the **expected output appears**.

A **bug** is an **unexpected problem in the program**. Bugs appear in many forms — and **some cannot be caught by reading the code**. That is why testing exists, in programming as everywhere: testing is what **assures quality** in education and in products, and in a program it is how errors are **found, to be debugged**.

**Debugging** means having **complete control over the program's execution** — and IDLE provides tools for it.

[Picture 31717 — an IDLE window with the Debug menu open and [DEBUG ON] at the prompt]

## Sub lesson 2 — Turning the debugger on — Debug → Debugger, [DEBUG ON]

To start, in the book's order:

1. From the IDLE menu bar, choose **Debug → Debugger**.
2. **`[DEBUG ON]` appears before the prompt (`>>>`)** — the sign the interpreter is ready.
3. **Running the file opens the debugger window**.

From there, the Debug Control window lets you pause, step and inspect — the next lesson works it in full. (For teachers and the curious: a good Python coding environment — IDEs and code editors — needs more than a text box; IDLE's debugger is this course's working example.)

## Say it to your companion

Tell your companion why testing must come before debugging, what a bug is, and the exact menu path that turns [DEBUG ON].

## Do It Yourself

1. Open IDLE, choose Debug → Debugger, and screenshot or copy the [DEBUG ON] prompt line.
2. Run a saved file with the debugger on and name the window that opens.
3. Write the definition of a bug from memory, then check it.
