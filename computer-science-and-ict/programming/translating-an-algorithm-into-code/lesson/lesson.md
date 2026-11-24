# Translating an Algorithm into Code

## Do it first

The algorithm is finished on paper. Now it must live in Java — saying exactly the same thing in a stricter tongue. Malaysia's programming chapter teaches translation as its own step. In this lesson you translate, structure by structure, and learn what translation must never change.

## Sub lesson 1 — Structure by structure

Translation works **structure by structure**, not line by wandering line: a pseudocode **sequence** becomes statements in the same order; a **selection** (IF…THEN…ELSE) becomes Java's if…else with its condition in brackets and its branches in braces; a **repetition** (WHILE or FOR) becomes Java's while or for. Variables in the algorithm are declared in the code before their first use, with the types the algorithm's values need. The flowchart translates the same way — each box and diamond has its code shape, and the arrows become the code's order and nesting.

In your mind's eye: structure by structure.

## Sub lesson 2 — What translation must never change

Translation changes the **language**, never the **logic**: the translated program must do **exactly** what the algorithm does — same steps, same tests, same order. Malaysia's check is a **parallel trace**: run one set of test values through the algorithm by hand and through the program, and the two must agree at every step. A disagreement is a translation fault — a dropped branch, a swapped comparison, a loop test turned upside down — and it is repaired in the code, against the algorithm, which remains the authority. Code written without an algorithm to answer to cannot be checked this way, which is why this course never writes it.

In your mind's eye: what translation must never change.

## Say it to your companion

Tell your companion, in your own words: Translation works **structure by structure**, not line by wandering line: a pseudocode **sequence** becomes statements in the same order; a **selection** (IF…THEN…ELSE) becomes Java's if…else with its condition in brackets and its branches in braces; a **repetition** (WHILE or FOR) becomes Java's while or for. Variables in the algorithm are declared in the code before their first use, with the types the algorithm's values need. The flowchart translates the same way — each box and diamond has its code shape, and the arrows become the code's order and nesting. Translation changes the **language**, never the **logic**: the translated program must do **exactly** what the algorithm does — same steps, same tests, same order. Malaysia's check is a **parallel trace**: run one set of test values through the algorithm by hand and through the program, and the two must agree at every step. A disagreement is a translation fault — a dropped branch, a swapped comparison, a loop test turned upside down — and it is repaired in the code, against the algorithm, which remains the authority. Code written without an algorithm to answer to cannot be checked this way, which is why this course never writes it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Structure by structure — not line by wandering line. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Statements in the same order. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: if…else — the condition in brackets, the branches in braces. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The logic — same steps, same tests, same order. Do this with a real example of your own and write or say how you know it is right.
