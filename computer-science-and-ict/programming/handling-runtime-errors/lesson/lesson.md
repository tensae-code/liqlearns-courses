# Handling Runtime Errors

## Do it first

The syntax is perfect. The logic is sound. Then a user types 0 for the divisor and the program dies in front of them. Runtime errors are the third kind of error — the kind only the run can reveal.

## Sub lesson 1 — Runtime errors — the kind only the run reveals

A **runtime error (σφάλμα εκτέλεσης)** is a fault that appears **while the program executes**: the data it meets breaks an operation — **division by zero**, a root of a negative number, a file that is not there, a value too large for its type. It differs from its two brothers: the **syntax error**, caught by the translator before the run, and the **logic error**, which runs quietly to a wrong answer. The runtime error **stops** the run — abnormal termination — unless the program was built expecting it.

In your mind's eye: runtime errors — the kind only the run reveals.

[Picture 47167 — runtime errors — the kind only the run reveals]

## Sub lesson 2 — Handling — expecting the blow and answering it

**Handling** a runtime error means building the program's answer **before** the blow lands: **check the dangerous data first** (is the divisor zero? does the file exist? is the value in range?) and give the program an honest road when the check fails — a message that names the trouble, a fresh chance to input, a safe ending instead of a crash. The chapter's rule is a design rule: every operation that *can* break on data must be met by its check, because the run will meet every data the writer did not imagine.

In your mind's eye: handling — expecting the blow and answering it.

[Picture 47168 — handling — expecting the blow and answering it]

## Say it to your companion

Tell your companion, in your own words: A **runtime error (σφάλμα εκτέλεσης)** is a fault that appears **while the program executes**: the data it meets breaks an operation — **division by zero**, a root of a negative number, a file that is not there, a value too large for its type. It differs from its two brothers: the **syntax error**, caught by the translator before the run, and the **logic error**, which runs quietly to a wrong answer. The runtime error **stops** the run — abnormal termination — unless the program was built expecting it. **Handling** a runtime error means building the program's answer **before** the blow lands: **check the dangerous data first** (is the divisor zero? does the file exist? is the value in range?) and give the program an honest road when the check fails — a message that names the trouble, a fresh chance to input, a safe ending instead of a crash. The chapter's rule is a design rule: every operation that *can* break on data must be met by its check, because the run will meet every data the writer did not imagine. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A fault that appears while the program executes, when the data breaks an operation. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Division by zero; a file that is not there (also root of a negative, value too large for its type). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Syntax is caught by the translator before the run; runtime appears in the run. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A logic error runs quietly to a wrong answer; a runtime error stops the run. Do this with a real example of your own and write or say how you know it is right.
