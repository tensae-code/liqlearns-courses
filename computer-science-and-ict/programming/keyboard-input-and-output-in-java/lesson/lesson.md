# Keyboard Input and Output in Java

## Do it first

A program that cannot be talked to is a poster. Malaysia's Java chapter teaches the conversation: the user types, the program reads; the program answers, the screen shows. In this lesson you write Java that takes keyboard input and prints output.

## Sub lesson 1 — Output — the program speaks

Java's printing workhorse is **System.out.println** — print this, then move to a new line; its sibling **System.out.print** stays on the same line. What is printed can be text in quotes, a variable's value, or the two joined with **+**: System.out.println("Mark: " + mark);. Output is where the program's inside becomes visible — Malaysia's programs print prompts as well as answers, because a silent program leaves the user not knowing it is waiting, or for what.

In your mind's eye: output — the program speaks.

[Picture 47226 — output — the program speaks]

## Sub lesson 2 — Input — the program listens

Keyboard input in Malaysia's Java work uses a **Scanner** on System.in: the program is set up with a Scanner, then reads with its methods — **nextInt()** for a whole number, **nextDouble()** for a decimal, **nextLine()** for a line of text. Each read **waits** until the user types and presses Enter, then hands the typed value over in the type the method promises — asking nextInt() for letters is a run-time fault. The chapter's shape for every such program is the conversation itself: prompt, read, process, print — the same input–process–output the course has used since pseudocode.

In your mind's eye: input — the program listens.

[Picture 47227 — input — the program listens]

## Say it to your companion

Tell your companion, in your own words: Java's printing workhorse is **System.out.println** — print this, then move to a new line; its sibling **System.out.print** stays on the same line. What is printed can be text in quotes, a variable's value, or the two joined with **+**: System.out.println("Mark: " + mark);. Output is where the program's inside becomes visible — Malaysia's programs print prompts as well as answers, because a silent program leaves the user not knowing it is waiting, or for what. Keyboard input in Malaysia's Java work uses a **Scanner** on System.in: the program is set up with a Scanner, then reads with its methods — **nextInt()** for a whole number, **nextDouble()** for a decimal, **nextLine()** for a line of text. Each read **waits** until the user types and presses Enter, then hands the typed value over in the type the method promises — asking nextInt() for letters is a run-time fault. The chapter's shape for every such program is the conversation itself: prompt, read, process, print — the same input–process–output the course has used since pseudocode. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Prints its value, then moves to a new line. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It stays on the same line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: With + — "Mark: " + mark. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: nextInt(). Do this with a real example of your own and write or say how you know it is right.
