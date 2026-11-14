# Declaring, Initialising and Assigning Variables

## Do it first

A variable has a biography: it is brought into being, given a first value, and given new values as the work goes. Malaysia's Java chapter names the three acts separately. In this lesson you learn declaration, initialisation and assignment — and the errors that live between them.

## Sub lesson 1 — Declaration and initialisation — being, and first value

**Declaration** brings the variable into being: a **type** and a **name** — int score; — after which the name exists but holds nothing usable. **Initialisation** gives the **first value**, often in the same breath: int score = 0;. Java refuses to use a variable that has not been given a value — reading an uninitialised variable is an error the compiler catches. A **constant** is declared with **final** and initialised once: final int PASS_MARK = 50; — its initialisation is also its only assignment, by law.

[Picture — Declaration and initialisation — being, and first value]

## Sub lesson 2 — Assignment — every later value

**Assignment** replaces a variable's value while the program runs: score = score + 5; — read it as 'score becomes score plus 5': the right side is worked out with the **old** value, then the result replaces it. Assignments may happen any number of times; a declaration happens **once** — declaring the same name twice is an error, assigning twice is ordinary work. Malaysia's three acts, kept apart, explain most beginner compiler messages: 'cannot find symbol' is a missing declaration, 'might not have been initialised' is a missing first value, and 'cannot assign to final' is an assignment aimed at a constant.

[Picture — Assignment — every later value]

## Say it to your companion

Tell your companion, in your own words: **Declaration** brings the variable into being: a **type** and a **name** — int score; — after which the name exists but holds nothing usable. **Initialisation** gives the **first value**, often in the same breath: int score = 0;. Java refuses to use a variable that has not been given a value — reading an uninitialised variable is an error the compiler catches. A **constant** is declared with **final** and initialised once: final int PASS_MARK = 50; — its initialisation is also its only assignment, by law. **Assignment** replaces a variable's value while the program runs: score = score + 5; — read it as 'score becomes score plus 5': the right side is worked out with the **old** value, then the result replaces it. Assignments may happen any number of times; a declaration happens **once** — declaring the same name twice is an error, assigning twice is ordinary work. Malaysia's three acts, kept apart, explain most beginner compiler messages: 'cannot find symbol' is a missing declaration, 'might not have been initialised' is a missing first value, and 'cannot assign to final' is an assignment aimed at a constant. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Declaration, initialisation, assignment. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A type and a name — being. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Its first value. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Replaces the variable's value while the program runs. Do this with a real example of your own and write or say how you know it is right.
