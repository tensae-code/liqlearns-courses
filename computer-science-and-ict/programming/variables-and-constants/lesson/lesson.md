# Variables and Constants

## Do it first

Two named boxes hold a program's values. One may change a hundred times a run; the other must never change at all. Malaysia teaches the pair formally in two school years and two languages. In this lesson you learn the difference — and why a program needs both kinds.

## Sub lesson 1 — Variables — values that change

A **variable** is a named store whose value **can change** while the program runs: a score starts at 0 and grows, a name is read in and replaced next run. In Python a variable is made by assigning (score = 0) and its type follows the value it holds; in Java it is declared with its type (int score = 0;). Changing a variable is normal work — assignment replaces the old value entirely; the old value is gone unless it was copied elsewhere first.

[Picture — Variables — values that change]

## Sub lesson 2 — Constants — values that are fixed

A **constant** (pemalar) is a named store whose value is **fixed when it is set and must not change** during the run: pi, the passing mark, the number of days in a week. Languages guard them differently — Python uses the capital-name convention (PI = 3.14159, a promise by the programmer), Java uses the keyword **final** (final int PASS_MARK = 50;), which the compiler enforces. Constants exist so fixed values have **one home**: change the rule once, in one place, and every use follows; a constant that could change silently would be a variable wearing a false name.

[Picture — Constants — values that are fixed]

## Say it to your companion

Tell your companion, in your own words: A **variable** is a named store whose value **can change** while the program runs: a score starts at 0 and grows, a name is read in and replaced next run. In Python a variable is made by assigning (score = 0) and its type follows the value it holds; in Java it is declared with its type (int score = 0;). Changing a variable is normal work — assignment replaces the old value entirely; the old value is gone unless it was copied elsewhere first. A **constant** (pemalar) is a named store whose value is **fixed when it is set and must not change** during the run: pi, the passing mark, the number of days in a week. Languages guard them differently — Python uses the capital-name convention (PI = 3.14159, a promise by the programmer), Java uses the keyword **final** (final int PASS_MARK = 50;), which the compiler enforces. Constants exist so fixed values have **one home**: change the rule once, in one place, and every use follows; a constant that could change silently would be a variable wearing a false name. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A named store whose value can change while the program runs. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A named store whose value is fixed when set and must not change during the run. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: By assigning — score = 0; its type follows the value. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Pi; the passing mark (also: days in a week). Do this with a real example of your own and write or say how you know it is right.
