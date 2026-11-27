# Reading Input With scanf and Printing With printf

## Do it first

A program that only prints its author's greeting is a poster. Give it scanf and it becomes a conversation: it asks, the user answers, it computes, printf reports. This lesson teaches the pair together, because in C they are one craft with two directions.

## Sub lesson 1 — printf — printing with format

**printf** prints text and values together: the **format string** carries ordinary words, **format specifiers** (%d, %f, %c — the data-types lesson's promises) where values go, and **escape sequences** for what keyboards cannot type directly — **\n** for a new line, **\t** for a tab. The values follow the string in order, one per specifier: `printf("Marks: %d\n", marks);`. What the user sees — labels, spacing, new lines — is entirely the programmer's courtesy, designed here and nowhere else.

In your mind's eye: printf — printing with format.

[Picture 47555 — printf — printing with format]

## Sub lesson 2 — scanf — reading into addresses; and the worked program

**scanf** reads the user's typed values **into variables** — and its famous peculiarity is the **&**: `scanf("%d", &age);` passes the variable's **address**, because scanf must *put* the value somewhere, not merely look at it. Forgetting the & is the C beginner's rite of passage. The book's worked whole joins the pair: read a **Celsius** temperature with scanf, compute **Fahrenheit = (C × 9/5) + 32**, print the answer with printf — input, process, output in C dress, and the template of every HSC program that follows.

In your mind's eye: scanf — reading into addresses; and the worked program.

[Picture 47556 — scanf — reading into addresses; and the worked program]

## Say it to your companion

Tell your companion, in your own words: **printf** prints text and values together: the **format string** carries ordinary words, **format specifiers** (%d, %f, %c — the data-types lesson's promises) where values go, and **escape sequences** for what keyboards cannot type directly — **\n** for a new line, **\t** for a tab. The values follow the string in order, one per specifier: `printf("Marks: %d\n", marks);`. What the user sees — labels, spacing, new lines — is entirely the programmer's courtesy, designed here and nowhere else. **scanf** reads the user's typed values **into variables** — and its famous peculiarity is the **&**: `scanf("%d", &age);` passes the variable's **address**, because scanf must *put* the value somewhere, not merely look at it. Forgetting the & is the C beginner's rite of passage. The book's worked whole joins the pair: read a **Celsius** temperature with scanf, compute **Fahrenheit = (C × 9/5) + 32**, print the answer with printf — input, process, output in C dress, and the template of every HSC program that follows. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Words, format specifiers and escape sequences. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Starts a new line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Moves to a tab stop. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: In order, one per specifier. Do this with a real example of your own and write or say how you know it is right.
