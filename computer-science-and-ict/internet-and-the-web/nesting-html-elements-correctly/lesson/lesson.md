# Nesting HTML Elements Correctly

## Do it first

Put a small box inside a big box, then try to close the big box first. Your hands refuse — the small box is in the way. HTML elements are boxes inside boxes, and they obey the same physics. This short lesson is the one rule that keeps a page's structure standing.

## Sub lesson 1 — Nesting — elements inside elements

HTML pages are built by **nesting**: an element placed inside another — a paragraph inside a section, a bold word inside the paragraph, a link inside the bold. The inside element is the **child**, its container the **parent**, and the browser builds the page as exactly this tree of boxes. Nesting is how structure is said: the tree is the document's skeleton, and every later skill — styling by CSS selectors, scripting — walks this tree.

In your mind's eye: nesting — elements inside elements.

## Sub lesson 2 — The mirror rule — last opened, first closed

The rule is one line: **elements close in the reverse order they opened** — `<p>…<b>…</b>…</p>`, never `<p>…<b>…</p>…</b>`. Wrongly nested (overlapping) tags make the browser guess where boxes end, and its guess may not be yours — the page breaks in ways that wander between browsers. The error-hunting lesson meets wrong nesting as a fault; this lesson is its prevention: write the closing tag the moment you write the opening one, then fill the middle, and the mirror can never break.

In your mind's eye: the mirror rule — last opened, first closed.

## Say it to your companion

Tell your companion, in your own words: HTML pages are built by **nesting**: an element placed inside another — a paragraph inside a section, a bold word inside the paragraph, a link inside the bold. The inside element is the **child**, its container the **parent**, and the browser builds the page as exactly this tree of boxes. Nesting is how structure is said: the tree is the document's skeleton, and every later skill — styling by CSS selectors, scripting — walks this tree. The rule is one line: **elements close in the reverse order they opened** — `<p>…<b>…</b>…</p>`, never `<p>…<b>…</p>…</b>`. Wrongly nested (overlapping) tags make the browser guess where boxes end, and its guess may not be yours — the page breaks in ways that wander between browsers. The error-hunting lesson meets wrong nesting as a fault; this lesson is its prevention: write the closing tag the moment you write the opening one, then fill the middle, and the mirror can never break. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Placing an element inside another element. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Child and parent. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The page's tree of boxes. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: CSS styling and scripting. Do this with a real example of your own and write or say how you know it is right.
