# The do-while Loop

## Do it first

A while loop asks permission before it starts. A do-while loop starts first and asks afterwards — this lesson is about when that difference matters.

## Sub lesson 1 — Body first, test after

In C++ the loop is written **do { … } while (condition);** — note the semicolon after the while. The body runs, **then** the condition is tested: true sends control back to the top of the body, false ends the loop. Because the test comes last, the body is guaranteed **at least one** execution — unlike while, which may run zero times.

[Picture — body first, test after]

## Sub lesson 2 — Choosing do-while — and its practice tasks

Use do-while when the first run must happen before a sensible test exists — the classic case is **asking for input and validating it**: show the prompt, read the answer, repeat while the answer is invalid. The book follows the structure with **practice tasks** (and a further set of exercises in the links-pass reading, §3.30): trace each task by writing the body's runs in a row and marking the test result after each run, so the stopping run is visible.

[Picture — choosing do-while — and its practice tasks]

## Say it to your companion

Tell your companion, in your own words: The do-while loop runs its body first and tests its condition afterwards, so the body always executes at least once; it repeats while the condition stays true and stops the first time the test fails — the right shape when the work must happen before any test makes sense. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: After the body has run. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The first test that comes out false. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Asking for input and validating the answer. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Write the body's runs in a row and mark each test result. Do this with a real example of your own and write or say how you know it is right.
