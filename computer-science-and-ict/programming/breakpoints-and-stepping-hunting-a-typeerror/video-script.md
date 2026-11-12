# Video script — Breakpoints and stepping — hunting a TypeError

The full walkthrough script for this lesson's doing — the breakpoint–Go–enter values–Step debugging run, filmed later; the script is the slot's written form until then. Super-simple voice, short lines.

---

Open IDLE. The debugger is ON — look: [DEBUG ON] at the prompt.

Here is our program. It divides two numbers.

The error hides where a number is divided by zero.
So we set the trap there.
Right-click the third print line. Set breakpoint.
See — the line turns **yellow**. The program will pause here.

Now press **Go**.
The program runs… and stops. It asks for the first number.
Type **50**. Enter.
It asks for the second number.
Type **0**. Enter.

Now — **Step**. One line at a time. Watch the values.
Step… step…

There! The error message appears.
Division by zero. The debugger walked us straight into it.

That is the hunt: breakpoint, Go, enter the values, Step — and the bug shows itself.
