# Video script — Nesting HTML Elements Correctly

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

HTML pages are built by **nesting**: an element placed inside another — a paragraph inside a section, a bold word inside the paragraph, a link inside the bold. The inside element is the **child**, its container the **parent**, and the browser builds the page as exactly this tree of boxes. Nesting is how structure is said: the tree is the document's skeleton, and every later skill — styling by CSS selectors, scripting — walks this tree.
The rule is one line: **elements close in the reverse order they opened** — `<p>…<b>…</b>…</p>`, never `<p>…<b>…</p>…</b>`. Wrongly nested (overlapping) tags make the browser guess where boxes end, and its guess may not be yours — the page breaks in ways that wander between browsers. The error-hunting lesson meets wrong nesting as a fault; this lesson is its prevention: write the closing tag the moment you write the opening one, then fill the middle, and the mirror can never break.
