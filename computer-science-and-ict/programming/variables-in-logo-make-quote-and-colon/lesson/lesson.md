# Variables in LOGO — MAKE, "name and :value

## Do it first

A jar on the table is labelled **size**, and inside it is the number 60. Three questions: if I point at the label and say "size", what have I named? If I open the jar, what do I get? And what single mark could tell LOGO which of the two I mean? This lesson is LOGO's answer.

## Variables — named containers

A **variable is the name of a memory location that can contain a value** — like a container with a "thing" inside. Names are strings of letters and can contain **letters, digits and underscore**. Variables have **no types** and **need not be declared before use**.

## Writing in — MAKE and the quote

A value is given with **MAKE**, using the **quoted name**:

`make "size 10`

— gives the variable **size** the value **10**. Words are quoted to tell LOGO **not to evaluate them**: the quote says "take this as the name itself."

## Reading out — the colon

To use the value inside a procedure or command, write a **colon in front of the name** — `:size`. Plain **"size" without the colon is treated as text, not the value**.

The book's worked examples, after `make "size 60`:

- `print :size/2` — prints **30**
- `print :size + 2` — prints **62**
- `print :size - 2` — prints **58** (printed in the book as `print size*2` in one line of §6.2 — taught here with the colon its own rule requires; see sources)

[Picture 12312 — a variable is a container]

And a word variable: `make "name "Hello` — then `print :name` outputs **Hello**. The word Hello itself is quoted so it is taken as a string.

**Tip — from us, not from the books:** say it as two hands — the quote hand puts the value in, the colon hand takes it out. If a print shows a word when you wanted a number, look for the missing colon first.

## Say it to your companion

Tell your companion what a variable is, how MAKE and the quote write a value in, and how the colon reads it out — with the size 60 examples.

## Do It Yourself

1. Run make "size 60 and the three prints; check them against the lesson's answers.
2. Make a word variable with your own name and print it with the colon.
3. Predict, then run: print "size after make "size 60. Say why the output is the word, not 60.
