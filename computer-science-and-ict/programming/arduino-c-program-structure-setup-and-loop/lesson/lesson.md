# Arduino C Program Structure — setup() and loop()

## Do it first

Arduino C program structure — every Arduino program (a sketch) in the C language has the same skeleton: setup() runs once at the start, loop() repeats forever

## Sub lesson 1 — The skeleton — two functions every sketch has

An Arduino program — a **sketch** — is written in **C**, and every sketch, from a blinking light to the smart bin, has the same basic structure (struktur dasar): two functions the board's system calls. **`void setup()`** holds what happens **once**, when the program starts: setting pin modes, starting the serial connection, preparing the parts. **`void loop()`** holds the program's life: when it finishes, the board calls it again, forever, until power ends. Indonesia's Grade 12 course teaches the skeleton before the commands, because every later line of Arduino code is filed in one of these two rooms.

In your mind's eye: the skeleton — two functions every sketch has.

## Sub lesson 2 — Writing in the skeleton — order, braces and the one-time test

The structure disciplines the writing: a command belongs in setup() if it must happen exactly once, in loop() if it is the behaviour repeated. The text rules of Arduino C ride on the skeleton — statements end with **semicolons**, blocks live inside **curly braces**, and `void` names a function that returns nothing. The beginner's standing fault is a one-time act written in loop() (a pin re-set a thousand times a second) or a behaviour trapped in setup() (run once, then silence). Read any sketch by its rooms and the program's whole shape is visible at a glance.

In your mind's eye: writing in the skeleton — order, braces and the one-time test.

## Say it to your companion

Tell your companion, in your own words: An Arduino program — a **sketch** — is written in **C**, and every sketch, from a blinking light to the smart bin, has the same basic structure (struktur dasar): two functions the board's system calls. **`void setup()`** holds what happens **once**, when the program starts: setting pin modes, starting the serial connection, preparing the parts. **`void loop()`** holds the program's life: when it finishes, the board calls it again, forever, until power ends. Indonesia's Grade 12 course teaches the skeleton before the commands, because every later line of Arduino code is filed in one of these two rooms. The structure disciplines the writing: a command belongs in setup() if it must happen exactly once, in loop() if it is the behaviour repeated. The text rules of Arduino C ride on the skeleton — statements end with **semicolons**, blocks live inside **curly braces**, and `void` names a function that returns nothing. The beginner's standing fault is a one-time act written in loop() (a pin re-set a thousand times a second) or a behaviour trapped in setup() (run once, then silence). Read any sketch by its rooms and the program's whole shape is visible at a glance. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A sketch — written in the C language Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: setup() and loop() Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Once, when the program starts Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: One-time preparation — pin modes, starting serial, preparing the parts Do this with a real example of your own and write or say how you know it is right.
