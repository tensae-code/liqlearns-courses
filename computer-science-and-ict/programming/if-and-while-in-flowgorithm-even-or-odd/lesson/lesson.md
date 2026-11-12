# If and while in Flowgorithm — even or odd

## Do it first

Two charts to read closely. One asks a single question — is this number even? — and forks. The other starts at 2 and keeps adding 2, printing as it goes, until a test says stop. Watch the GIF walk the second chart round: 2, 4, 6, 8 — then the test fails, and the flow leaves. Which chart needs a loop, and which must never have one?

## Even or odd — a decision, not a loop

Read the first flowchart closely: declare the variable, prompt 'Enter an integer:', accept it, then a decision diamond testing number % 2 = 0. The % is the modulo operator, giving the remainder of an integer division — 14 % 3 is 2. Remainder 0 flows to 'number is even'; otherwise to 'number is odd'. The decision / if structure, not a loop, is the right tool — one number, one question, one fork.

[Picture 20940 — If and while — a diamond fork and a while loop]

## Printing evens under 10 — a while loop

The second chart: declare num, assign 2 — assignment is making a variable hold a value — then a while loop testing num < 10. Inside: output num and add 2 to num, returning to the test each time until it becomes FALSE and the flow exits. The printed line is 2, 4, 6, 8 — trace it in the GIF, round by round, and watch num reach 10 and stop the loop.

[GIF 20954 — tracing the while loop as num grows 2, 4, 6]

## Say it to your companion

Tell your companion, in your own words: a decision diamond tests number % 2 = 0 to sort even from odd, and a while loop prints the even numbers under 10 — selection for the first job, repetition for the second. Then name the key words of this lesson — the modulo operator %, the even test, assignment, a while loop — and say what each one means.

## Do It Yourself

1. Test 23 and 40 for evenness, showing the % working.
2. List num's values round by round in the while chart.
3. Say what changes if the while test were num <= 10.
