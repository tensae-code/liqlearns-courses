# Detecting Errors in Pseudocode and Flowcharts

## Do it first

A flowchart can be wrong before a line of code is written: a loop that never ends, a decision whose No path goes nowhere. Malaysia teaches error-hunting in pseudocode and flowcharts in three different school years. In this lesson you learn to trace an algorithm on paper and catch its faults while they are still cheap.

## Sub lesson 1 — Tracing — running the algorithm by hand

**Detecting** begins with a **trace**: choose test values, then follow the pseudocode or flowchart **step by step on paper**, writing every variable's value after every step. The trace exposes what reading hides: a value that never changes, a step that uses a value before it exists, a path that is never reached. Malaysia's rule is that the trace is worked **in the algorithm's own order**, never in the order you expect — expectation is what hid the fault.

In your mind's eye: tracing — running the algorithm by hand.

[Picture 47023 — tracing — running the algorithm by hand]

## Sub lesson 2 — The faults a trace exposes — and fixing them

The common logic faults are: a **loop with no way out** (its test can never become false — the increment or change is missing); a **decision missing a path** (the No branch joins nothing, or two paths cross); a **wrong order** (a total averaged before it is complete); and a **wrong test** (comparing with = when the plan needs ≥). Fixing is done **in the algorithm** — the pseudocode line or flowchart box is corrected and the trace re-run from the top, because a fix in a plan is one line; the same fix in finished code is a hunt.

In your mind's eye: the faults a trace exposes — and fixing them.

[Picture 47024 — the faults a trace exposes — and fixing them]

## Say it to your companion

Tell your companion, in your own words: **Detecting** begins with a **trace**: choose test values, then follow the pseudocode or flowchart **step by step on paper**, writing every variable's value after every step. The trace exposes what reading hides: a value that never changes, a step that uses a value before it exists, a path that is never reached. Malaysia's rule is that the trace is worked **in the algorithm's own order**, never in the order you expect — expectation is what hid the fault. The common logic faults are: a **loop with no way out** (its test can never become false — the increment or change is missing); a **decision missing a path** (the No branch joins nothing, or two paths cross); a **wrong order** (a total averaged before it is complete); and a **wrong test** (comparing with = when the plan needs ≥). Fixing is done **in the algorithm** — the pseudocode line or flowchart box is corrected and the trace re-run from the top, because a fix in a plan is one line; the same fix in finished code is a hunt. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A trace — running the algorithm by hand, step by step on paper. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Every variable's value after every step. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A value that never changes; a step using a value before it exists (also: a path never reached). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A loop with no way out — its test can never become false. Do this with a real example of your own and write or say how you know it is right.
