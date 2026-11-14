# Built-In Functions in BASIC — SQR, SIN, LEFT$ and LEN

## Do it first

Find the square root of 81 by hand — then imagine a program that must do it a thousand times. BASIC refuses to make you write that work: it is already written, inside the language, waiting for its name. This lesson opens the toolbox.

## Sub lesson 1 — Built-in functions — work the language does for you

BASIC carries a toolbox of **built-in (reserved) functions**: named pieces of work the language itself performs. You give a function a value and it hands back a result — no program of yours defines how. The mathematical family comes first in Sudan's book: **SQR** gives a number's square root, **SIN** its sine, and their fellows give cosines, tangents, absolute values and whole parts. Writing `LET R = SQR(81)` stores 9 — the root was found by the language, not by your lines.

[Picture — Built-in functions — work the language does for you]

## Sub lesson 2 — String functions — LEFT$ and LEN

The second family works on **strings** — text held in string variables. **LEN** counts a string's characters: `LEN("KHARTOUM")` is 8. **LEFT$** cuts from the left: `LEFT$("KHARTOUM", 4)` is "KHAR" — the first four characters. Their partners cut from the right and the middle. A built-in function is recognised the same way in both families: a reserved name, a value in brackets, a single result out. The next lesson turns the idea around — functions the programmer defines for herself.

[Picture — String functions — LEFT$ and LEN]

## Say it to your companion

Tell your companion, in your own words: BASIC carries a toolbox of built-in (reserved) functions: named pieces of work the language itself performs. The second family works on strings — text held in string variables. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A named piece of work the language itself performs — you give a value, it hands back a result. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 9 — the square root of 81. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 8 — the count of the string's characters. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A reserved name, a value in brackets, a single result out. Do this with a real example of your own and write or say how you know it is right.
