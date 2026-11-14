# Video script — Control Structures in JavaScript

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

JavaScript chooses with **if (condition) { … } else if (condition) { … } else { … }**: the condition sits in **brackets** and is tested as true or false, the chosen branch's **braces** run, and the rest are skipped. Conditions are built with comparisons (==, !=, >, <, >=, <=) and joined with logical operators (&& for AND, || for OR, ! for NOT). Client-side, the choices are the page's judgements: which message a form answer earns, which menu a visitor's level opens.
JavaScript repeats with **for** — for (let i = 1; i <= 5; i++) { … } gathers start, test and step in one line, for a count known in advance — and **while** — while (condition) { … } repeats until its test fails, for a count known only by the running. The loop's **body must move the test toward ending** (i++ inside the for's line; the change written inside a while's body), or the page hangs in an endless loop — the browser's most public fault. Malaysia's scripts use the pair for the page's repetitive work: listing items, checking each field of a form, totalling a column of marks.
