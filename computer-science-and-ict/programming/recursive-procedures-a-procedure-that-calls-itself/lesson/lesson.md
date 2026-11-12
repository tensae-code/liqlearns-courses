# Recursive procedures — a procedure that calls itself

## Do it first

Write the steps you followed this morning: waking, getting up, and reaching school. In order. Those steps are a procedure from your own life — the book starts here too. Keep the list; the end of this lesson asks what would make it recursive.

## What recursive means

A procedure is **recursive when it invokes a copy of itself** — a call of the procedure within the procedure. Its meaning works by the same copy rule as ordinary procedure calls: when the procedure runs, it meets its own name inside itself, and runs a copy of itself again.

The book grounds the idea in everyday procedures first: the steps followed on waking — **get out of bed, clean up, dress, eat breakfast, brush teeth, go to school** — steps that make something happen.

## The book's star — read what the code does

The book's example is a star procedure:

```
to star
repeat 100 [fd 100 rt 144]
end
```

Its output is a many-pointed star. Now read the code the way LOGO reads it: the body holds one command, **REPEAT 100 [fd 100 rt 144]** — go forward 100, turn 144 degrees, one hundred times. **The procedure never calls itself** — the word **star** does not appear inside **star**. So what the code actually does is **repeat**, beautifully — but repetition is not recursion. A truly recursive procedure carries its own name inside its body. Learn the book's definition, use the book's star as the drawing — and keep the test: *does the name call itself?*

[Picture 12315 — the star procedure]

[GIF 12316 — the star draws itself]

## Say it to your companion

Tell your companion what makes a procedure recursive, the waking-up steps, and why the star's code is repetition, not recursion.

## Do It Yourself

1. Write the definition of a recursive procedure from memory.
2. Look at the star code: point to the exact place a self-call would have to stand, and write what is there instead.
3. Take your morning procedure: what one change would make it recursive? (A step that runs the whole morning again.) Say why real mornings are not recursive.
