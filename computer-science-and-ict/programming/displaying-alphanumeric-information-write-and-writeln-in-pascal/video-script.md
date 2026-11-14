# Video script — Displaying Alphanumeric Information — write and writeln in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**write** displays its parameters and leaves the cursor where it stopped; **writeln** displays and then moves to a **new line**. The parameters may be **numbers, characters, strings in apostrophes, or whole expressions** — each is evaluated and shown in turn: `writeln('Sum = ', s)` prints the text, then the value of s. Showing **alphanumeric information** — letters and digits together, the screen's whole alphabet — is these two procedures' job; C++ does the same work with `cout <<`.
A parameter may carry a **format**: `write(x:8)` reserves **8 positions** for x, right-aligned in its field — the trick that builds straight columns in tables; `write(r:8:2)` adds **2 decimals** for a real. Unformatted reals print in long exponent form, so formats are not decoration but legibility: money with two decimals, tables with aligned columns, labels glued to values with spaces inside the strings. The display is the program's face to its user — this section teaches it as a craft, not an afterthought.
