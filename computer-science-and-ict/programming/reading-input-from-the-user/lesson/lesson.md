# Reading Input from the User

## Do it first

Programs that only ever use values the programmer typed into the code are toys. This lesson opens the program to the person using it.

## Sub lesson 1 — Prompt, then read

The pattern is two steps: **cout** a prompt ("Enter your age: "), then **cin >> age;** waits for typing, converts what was typed to age's **type**, and stores it. The **>>** points the way the data flows — from the keyboard stream into the variable. Without the prompt the program waits in silence and the user cannot tell it is waiting at all.

[Picture — prompt, then read]

## Sub lesson 2 — Several values and further practice

Reads chain — **cin >> a >> b;** takes two values separated by spaces or new lines — and a program can read as many values as it has statements for. The book returns to entering data for **further practice** (§3.23) after the if-else work: reading a value and immediately deciding on it is the first shape of nearly every interactive program, so the practice set drills the prompt-read-decide rhythm.

[Picture — several values and further practice]

## Say it to your companion

Tell your companion, in your own words: Input lets the user hand values to a running program: in C++ cin >> variable pulls the next typed value into the variable (converting it to the variable's type), a prompt printed first tells the user what is expected, and reading several values — or practising on further examples — follows the same one-pattern shape. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Pulls the next typed value into the variable. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It is converted to the variable's type. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Chained — cin >> a >> b;. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Prompt, read, decide. Do this with a real example of your own and write or say how you know it is right.
