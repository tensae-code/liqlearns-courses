# Procedures and Functions in JavaScript

## Do it first

A page's script grows: the same checking is needed in three places. Malaysia's JavaScript chapter answers with the course's old friends in new dress — functions. In this lesson you declare, call and answer with JavaScript functions.

## Sub lesson 1 — Declaring and calling

A JavaScript function is **declared once** — function greet(name) { … } — naming it, listing its **parameters** in brackets, and writing its body in braces. It is **called** wherever its work is needed — greet('Aina'); — with **arguments** handed in for the parameters. In this course's language, a JavaScript function that only **does a job** (shows a message) works as a **procedure**; one that **answers a value** works as a function proper. The declaration sits apart from the calls, so the script's reading order is: definitions gathered, then the story that uses them.

In your mind's eye: declaring and calling.

## Sub lesson 2 — Returning — the function's answer

A function answers through **return**: return total; ends the function at once and hands the value back to the caller, where it can be stored, printed, or used inside a larger expression — let avg = average(m1, m2);. A function with no return hands back **undefined** — correct for procedures, a silent fault for a function whose answer is then used in a sum. Malaysia's rule from the functions strand holds in JavaScript unchanged: one job per function, a name that says the job, and parameters for everything the job needs from outside — a function that reaches for the page's loose variables instead of its parameters cannot be tested alone, and what cannot be tested alone will be debugged in company.

In your mind's eye: returning — the function's answer.

## Say it to your companion

Tell your companion, in your own words: A JavaScript function is **declared once** — function greet(name) { … } — naming it, listing its **parameters** in brackets, and writing its body in braces. It is **called** wherever its work is needed — greet('Aina'); — with **arguments** handed in for the parameters. In this course's language, a JavaScript function that only **does a job** (shows a message) works as a **procedure**; one that **answers a value** works as a function proper. The declaration sits apart from the calls, so the script's reading order is: definitions gathered, then the story that uses them. A function answers through **return**: return total; ends the function at once and hands the value back to the caller, where it can be stored, printed, or used inside a larger expression — let avg = average(m1, m2);. A function with no return hands back **undefined** — correct for procedures, a silent fault for a function whose answer is then used in a sum. Malaysia's rule from the functions strand holds in JavaScript unchanged: one job per function, a name that says the job, and parameters for everything the job needs from outside — a function that reaches for the page's loose variables instead of its parameters cannot be tested alone, and what cannot be tested alone will be debugged in company. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Once, with the function keyword — name, parameters in brackets, body in braces. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Arguments, for the parameters. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A procedure. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Through return — which ends the function at once and hands the value to the caller. Do this with a real example of your own and write or say how you know it is right.
