# Handling Input Errors with Try and Except

## Do it first

Egypt's Grade 9 input lesson is not about the debugger — it is about the user. People type letters where numbers belong, leave fields empty and paste the wrong thing, and a program that crashes on the first surprise is unfinished. This lesson teaches validation and Python's try/except: expecting the error, catching it, and answering it like a host instead of a trapdoor.

## Sub lesson 1 — Validate first — check before you trust

**Validation** checks input **before** the program trusts it: is something there at all, is it the right **kind** (a number, where a number is needed), is it in the allowed **range**? Each failed check earns a **clear message** and another chance — 'Marks run from 0 to 100; you typed 140' teaches; a silent wrong answer corrupts. Egypt places this in the same lesson as error handling because the two are one discipline: most input errors should never become program errors at all, caught at the door by checks written from knowing exactly what the program needs.

[Picture — Validate first — check before you trust]

## Sub lesson 2 — Try and except — when the error still comes

Some errors survive validation — a conversion that fails, a file that is not there — and Python's answer is **try/except**: the risky lines go in the **try** block; if one raises an error, Python jumps to the **except** block instead of crashing, and the program responds — a message, a default, another attempt — and continues. The craft is aim: wrap the **few lines** that can fail, name the **specific** error where you can, and never let an except block swallow a fault silently, or real bugs will hide inside it. Egypt's Grade 9 book teaches this to pupils whose other error lesson is the IDLE debugger — the pair is complete: the debugger finds the program's faults; try/except survives the user's.

[Picture — Try and except — when the error still comes]

## Say it to your companion

Tell your companion, in your own words: **Validation** checks input **before** the program trusts it: is something there at all, is it the right **kind** (a number, where a number is needed), is it in the allowed **range**? Each failed check earns a **clear message** and another chance — 'Marks run from 0 to 100; you typed 140' teaches; a silent wrong answer corrupts. Egypt places this in the same lesson as error handling because the two are one discipline: most input errors should never become program errors at all, caught at the door by checks written from knowing exactly what the program needs. Some errors survive validation — a conversion that fails, a file that is not there — and Python's answer is **try/except**: the risky lines go in the **try** block; if one raises an error, Python jumps to the **except** block instead of crashing, and the program responds — a message, a default, another attempt — and continues. The craft is aim: wrap the **few lines** that can fail, name the **specific** error where you can, and never let an except block swallow a fault silently, or real bugs will hide inside it. Egypt's Grade 9 book teaches this to pupils whose other error lesson is the IDLE debugger — the pair is complete: the debugger finds the program's faults; try/except survives the user's. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Checking input before the program trusts it. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Something is there, it is the right kind, and it is in the allowed range. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: Respond — a message, a default, another attempt — and let the program continue. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: The few lines that can fail — no more. Do this with a real example of your own and write or say how you know it is right.
