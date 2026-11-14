# Video script — Detecting Errors in Pseudocode and Flowcharts

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Detecting** begins with a **trace**: choose test values, then follow the pseudocode or flowchart **step by step on paper**, writing every variable's value after every step. The trace exposes what reading hides: a value that never changes, a step that uses a value before it exists, a path that is never reached. Malaysia's rule is that the trace is worked **in the algorithm's own order**, never in the order you expect — expectation is what hid the fault.
The common logic faults are: a **loop with no way out** (its test can never become false — the increment or change is missing); a **decision missing a path** (the No branch joins nothing, or two paths cross); a **wrong order** (a total averaged before it is complete); and a **wrong test** (comparing with = when the plan needs ≥). Fixing is done **in the algorithm** — the pseudocode line or flowchart box is corrected and the trace re-run from the top, because a fix in a plan is one line; the same fix in finished code is a hunt.
