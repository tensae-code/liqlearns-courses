# Video script — Finding Errors in HTML

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Most beginner HTML errors are one of four: an **unclosed tag** (a <b> or <p> with no closing tag, so its effect runs to the page's end); **wrong nesting** (tags closed in the wrong order — <b><i>text</b></i> instead of <b><i>text</i></b>); a **misspelled tag or attribute name**, which the browser silently ignores; and **missing quotes** around an attribute value, which breaks the attribute. Browsers rarely complain — they guess and carry on — so the page, not an error message, is the evidence.
Finding the fault is a **comparison**: look at what the page **shows**, name exactly what is wrong and where it starts, then read the code **from that place** for the four faults. The fault is almost always at or just before the place where the wrongness starts — a heading that never ends began at its unclosed tag. Malaysia's method is to fix **one fault at a time** and re-open the page after each fix, so every change's effect is seen on its own; guessing in batches hides which fix worked.
