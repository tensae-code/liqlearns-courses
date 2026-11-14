# Text Files in Pascal and C++

## Do it first

The files chapter's most useful citizen: the text file — the format every other program can read, the notebook paper of computing. Grade 11 gives it the section after files in general and sequential files, as their main application.

## Sub lesson 1 — A file of characters and lines

A **text file** is a file whose data are **characters**, organised into **lines** ended by an end-of-line mark. In Pascal it is declared as a variable of type **text**; the ordinary instructions change their address: `writeln(f, x)` writes to the file f, `read(f, x)` reads from it. Numbers are stored as their **printed characters** — '4', '7' — not as their binary values, which is why text files open in any editor and travel between any programs and machines.

[Picture — A file of characters and lines]

## Sub lesson 2 — Ends of things — eof and eoln

Two tests guard text work. **eof(f)** is true when the file's reading has reached the **end of the file**; **eoln(f)** is true at the **end of the current line**. The canonical reading loop — `while not eof(f) do begin readln(f, line); process(line); end` — trusts eof to stop exactly after the last line. Writing mirrors reading: writeln lays lines, and close seals the file. The standing errors are the chapter's warnings: reading past the end, and numbers read as characters when the spaces between them are skipped wrongly.

[Picture — Ends of things — eof and eoln]

## Say it to your companion

Tell your companion, in your own words: A **text file** is a file whose data are **characters**, organised into **lines** ended by an end-of-line mark. In Pascal it is declared as a variable of type **text**; the ordinary instructions change their address: `writeln(f, x)` writes to the file f, `read(f, x)` reads from it. Numbers are stored as their **printed characters** — '4', '7' — not as their binary values, which is why text files open in any editor and travel between any programs and machines. Two tests guard text work. **eof(f)** is true when the file's reading has reached the **end of the file**; **eoln(f)** is true at the **end of the current line**. The canonical reading loop — `while not eof(f) do begin readln(f, line); process(line); end` — trusts eof to stop exactly after the last line. Writing mirrors reading: writeln lays lines, and close seals the file. The standing errors are the chapter's warnings: reading past the end, and numbers read as characters when the spaces between them are skipped wrongly. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Characters, organised into lines ended by an end-of-line mark. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: As a variable of type text. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: By naming it first — writeln(f, x) writes to f. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: As their printed characters, not their binary values. Do this with a real example of your own and write or say how you know it is right.
