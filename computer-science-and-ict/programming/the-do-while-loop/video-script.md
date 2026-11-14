# Video script — The do-while Loop

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In C++ the loop is written **do { … } while (condition);** — note the semicolon after the while. The body runs, **then** the condition is tested: true sends control back to the top of the body, false ends the loop. Because the test comes last, the body is guaranteed **at least one** execution — unlike while, which may run zero times.
Use do-while when the first run must happen before a sensible test exists — the classic case is **asking for input and validating it**: show the prompt, read the answer, repeat while the answer is invalid. The book follows the structure with **practice tasks** (and a further set of exercises in the links-pass reading, §3.30): trace each task by writing the body's runs in a row and marking the test result after each run, so the stopping run is visible.
