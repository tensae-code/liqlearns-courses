# Video script — Text Files in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **text file** is a file whose data are **characters**, organised into **lines** ended by an end-of-line mark. In Pascal it is declared as a variable of type **text**; the ordinary instructions change their address: `writeln(f, x)` writes to the file f, `read(f, x)` reads from it. Numbers are stored as their **printed characters** — '4', '7' — not as their binary values, which is why text files open in any editor and travel between any programs and machines.
Two tests guard text work. **eof(f)** is true when the file's reading has reached the **end of the file**; **eoln(f)** is true at the **end of the current line**. The canonical reading loop — `while not eof(f) do begin readln(f, line); process(line); end` — trusts eof to stop exactly after the last line. Writing mirrors reading: writeln lays lines, and close seals the file. The standing errors are the chapter's warnings: reading past the end, and numbers read as characters when the spaces between them are skipped wrongly.
