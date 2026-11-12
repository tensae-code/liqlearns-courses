# Commenting out code in IDLE — Alt+3 and Alt+4

## Do it first

In IDLE, type a two-line program, select BOTH lines with the mouse, and press **Alt+3**. Both lines gain a `#` at once — no typing hashes line by line. Run the file: nothing prints. Now select the lines again and press **Alt+4**: the hashes vanish and the program runs again. Two keystrokes run this whole lesson.

## Sub lesson 1 — Comment Out Region — select, Format, Alt+3

IDLE's commenting features sit under the **Format** menu:

1. **Select** the part of the code to comment out.
2. Choose **Format → Comment Out Region** — or press **Alt+3**.

The selected lines gain `#` marks in one menu action. The IDLE keystroke in the teacher key is the same: put the cursor at the start of the code fragment and use **Alt+3** to insert the comment symbol. Watch the GIF: the `#` marks appear on the selected lines together.

[Picture 31714 — the IDLE Format menu open with Comment Out Region highlighted]

[GIF 31728 — selected lines gaining # marks in one menu action]

[GIF 31732 — lines of code being commented out one by one until the output window goes blank]

## Sub lesson 2 — Uncomment Region — Alt+4 — and hunting errors by commenting

To **uncomment**: select the part, then **Format → Uncomment Region** — or press **Alt+4**.

The working method built on these two keys:

- Comment out one fragment, run, uncomment, comment out the other fragment, run — and compare outputs.
- Add a **describing comment** to say what a fragment does.
- When a program breaks after new lines are added, **comment out the new lines** — that is a way to hunt down **which lines introduced an error**: if the program works with them out, the fault lives in them.

And the end state to recognise: comment out lines **one by one until every line is out, and the output window goes blank** — a fully commented program does nothing.

## Say it to your companion

Show your companion the two keys — Alt+3 out, Alt+4 back — and explain how commenting out new lines hunts an error.

## Do It Yourself

1. In IDLE, comment out the first fragment of a two-fragment program with Alt+3, run, then swap with Alt+4.
2. Add a describing comment to a fragment using the Format menu.
3. Break a working program by adding a faulty line, then hunt it by commenting out new lines.
