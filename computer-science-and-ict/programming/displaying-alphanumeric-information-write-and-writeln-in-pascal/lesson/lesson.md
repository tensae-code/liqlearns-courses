# Displaying Alphanumeric Information — write and writeln in Pascal

## Do it first

A program that computes in silence is half a program. Two Moldova books teach the showing as its own instruction family: write and writeln, the voices of every Pascal program in the course.

## Sub lesson 1 — write and writeln — showing values and texts

**write** displays its parameters and leaves the cursor where it stopped; **writeln** displays and then moves to a **new line**. The parameters may be **numbers, characters, strings in apostrophes, or whole expressions** — each is evaluated and shown in turn: `writeln('Sum = ', s)` prints the text, then the value of s. Showing **alphanumeric information** — letters and digits together, the screen's whole alphabet — is these two procedures' job; C++ does the same work with `cout <<`.

In your mind's eye: write and writeln — showing values and texts.

[Picture 47033 — write and writeln — showing values and texts]

## Sub lesson 2 — Formats — width and decimals

A parameter may carry a **format**: `write(x:8)` reserves **8 positions** for x, right-aligned in its field — the trick that builds straight columns in tables; `write(r:8:2)` adds **2 decimals** for a real. Unformatted reals print in long exponent form, so formats are not decoration but legibility: money with two decimals, tables with aligned columns, labels glued to values with spaces inside the strings. The display is the program's face to its user — this section teaches it as a craft, not an afterthought.

In your mind's eye: formats — width and decimals.

[Picture 47034 — formats — width and decimals]

## Say it to your companion

Tell your companion, in your own words: **write** displays its parameters and leaves the cursor where it stopped; **writeln** displays and then moves to a **new line**. The parameters may be **numbers, characters, strings in apostrophes, or whole expressions** — each is evaluated and shown in turn: `writeln('Sum = ', s)` prints the text, then the value of s. Showing **alphanumeric information** — letters and digits together, the screen's whole alphabet — is these two procedures' job; C++ does the same work with `cout <<`. A parameter may carry a **format**: `write(x:8)` reserves **8 positions** for x, right-aligned in its field — the trick that builds straight columns in tables; `write(r:8:2)` adds **2 decimals** for a real. Unformatted reals print in long exponent form, so formats are not decoration but legibility: money with two decimals, tables with aligned columns, labels glued to values with spaces inside the strings. The display is the program's face to its user — this section teaches it as a craft, not an afterthought. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: write leaves the cursor where it stopped; writeln moves to a new line after displaying. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Numbers, characters, strings in apostrophes, and whole expressions. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The text 'Sum = ', then the value of s. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Letters and digits together — everything the screen can show as text. Do this with a real example of your own and write or say how you know it is right.
