# Video script — Procedures and Functions in JavaScript

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A JavaScript function is **declared once** — function greet(name) { … } — naming it, listing its **parameters** in brackets, and writing its body in braces. It is **called** wherever its work is needed — greet('Aina'); — with **arguments** handed in for the parameters. In this course's language, a JavaScript function that only **does a job** (shows a message) works as a **procedure**; one that **answers a value** works as a function proper. The declaration sits apart from the calls, so the script's reading order is: definitions gathered, then the story that uses them.
A function answers through **return**: return total; ends the function at once and hands the value back to the caller, where it can be stored, printed, or used inside a larger expression — let avg = average(m1, m2);. A function with no return hands back **undefined** — correct for procedures, a silent fault for a function whose answer is then used in a sum. Malaysia's rule from the functions strand holds in JavaScript unchanged: one job per function, a name that says the job, and parameters for everything the job needs from outside — a function that reaches for the page's loose variables instead of its parameters cannot be tested alone, and what cannot be tested alone will be debugged in company.
