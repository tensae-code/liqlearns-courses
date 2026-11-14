# Nested if-else

## Do it first

Some decisions come in layers: first whether, then which kind. This lesson builds selections inside selections — and keeps them readable.

## Sub lesson 1 — A choice inside a choice

**Nesting** puts an if-else **inside the branch** of another: if the outer condition holds, the inner if-else runs and picks between its two ways; if not, the outer else runs. The inner question is only asked when the outer answer makes it meaningful — pass the exam first, **then** ask distinction or plain pass.

[Picture — a choice inside a choice]

## Sub lesson 2 — Indentation and the dangling else

Nesting multiplies a known danger: an **else pairs with the nearest unmatched if**, whatever the writer intended — so **indentation** must honestly mirror the pairing, and braces should wrap branches whenever misreading is possible. The book teaches nesting through **exercises** (§3.24): trace each by walking the conditions in order and marking the one path taken.

[Picture — indentation and the dangling else]

## Say it to your companion

Tell your companion, in your own words: A nested if-else is a selection placed inside another selection's branch: the outer test narrows the situation, the inner test decides within it — used when the second question only makes sense after the first is answered, and kept readable by strict indentation that shows which else belongs to which if. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A selection inside another selection's branch. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: When the second question only makes sense after the first. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The nearest unmatched if. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Braces around branches. Do this with a real example of your own and write or say how you know it is right.
