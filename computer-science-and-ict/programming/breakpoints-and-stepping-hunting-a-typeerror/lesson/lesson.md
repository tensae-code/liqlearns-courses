# Breakpoints and stepping — hunting a TypeError

## Do it first

A program adds two typed numbers — and crashes with a **TypeError**, because typed input arrives as text and text cannot be added to a number the way the program tries. Reading the code, the fault hides. So we hunt it the debugger's way: pause the program ON a chosen line, then walk it line by line, watching the values, until the error shows itself. That walk — breakpoint, Go, Step, fix, re-check — is this lesson, and its full walkthrough script is the video script.

## Sub lesson 1 — Debug Control — Go, Step, Over, and watching variables

In the **Debug Control** window you **inspect variables' values as code executes**. Its buttons:

- **Go** — advance execution as normal **until a breakpoint or an input request**;
- **Step** — see the internal commands for the current line and **move to the next**;
- **Over** — **line-by-line execution**.

This course works with **Go** and **Step**.

[Picture 31718 — a program line highlighted yellow beside a Debug Control panel with Go and Step labelled, values 50 and 0 entered]

[GIF 31733 — the debugger stepping from the breakpoint into the error message]

[GIF 31734 — execution pausing at a yellow breakpoint line, then stepping line by line]

## Sub lesson 2 — Breakpoints — the yellow pause line — and the trace-and-fix

A **breakpoint** is a line you select as a **pause place**:

- **Right-click the line** to set it — it **highlights yellow**; set **as many as you like**.
- **Right-click again → Clear Breakpoint** to remove it.

**The traced example, in order:** run with a breakpoint set → press **Go** → **enter the two numbers** requested → **Step** line by line until a **TypeError is displayed, highlighted** → go to the source → **fix the problem by casting the input to integer** — `int(input(...))`, because keyboard input is text → **repeat the steps to check the bug is fixed**. Verified in Python 3: text plus a number raises TypeError; after the int() cast the same addition gives the numeric answer (50 + 10 = 60 in the band's check run).

**The closing walkthrough — division:** the error is predicted where a number is **divided by zero**, so the **breakpoint is set on the third print statement**; **Go** is pressed; **50** is entered for the first number and **0** for the second; **Step** is pressed — and the **error message appears** (ZeroDivisionError, verified). Watch the GIF: the debugger steps from the breakpoint straight into the error.

## Say it to your companion

Walk your companion through the whole hunt: breakpoint set, Go, values entered, Step, error found, int() fix, re-check — the divide-by-zero numbers are 50 and 0.

## Do It Yourself

1. Set a breakpoint on a chosen line (yellow), run with Go, then clear it.
2. Reproduce the TypeError trace: breakpoint, Go, enter two values, Step to the error.
3. Fix the traced program with int() and repeat the full trace to verify the fix.
