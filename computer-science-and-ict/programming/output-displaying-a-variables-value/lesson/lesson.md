# Output — Displaying a Variable's Value

## Do it first

A program that computes silently might as well not compute. This lesson is about showing results — and about the difference between printing words and printing what a variable holds.

## Sub lesson 1 — Text, values and results

**cout << "Total: " << total;** prints the quoted **text exactly**, then the **value** of total — no quotes, so the machine looks the name up. Leave the quotes on and the program prints the word total instead of its value: the classic first output bug. Items chain in one statement, in the order they are to appear.

[Picture — text, values and results]

## Sub lesson 2 — Lines, spaces and layout

Output runs together unless the program **separates** it: spaces inside the text, **endl** (or '\n') for a new line. A result table is just disciplined layout — label, value, new line, repeated. What the user sees is the program's whole reputation, so this book splits output into its own section (§3.16), right after assigning values and before expressions.

[Picture — lines, spaces and layout]

## Say it to your companion

Tell your companion, in your own words: Output shows the user what the program holds: in C++ cout sends a stream of items to the screen — text in quotes printed exactly as written, variables printed as their current values, expressions printed as their results — chained with << and finished, when a new line is wanted, with endl or a newline. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The screen. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Its current value. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Ends the line — the next output starts a new line. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: So results do not run together unreadably. Do this with a real example of your own and write or say how you know it is right.
