# Video script — Reading Input With scanf and Printing With printf

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**printf** prints text and values together: the **format string** carries ordinary words, **format specifiers** (%d, %f, %c — the data-types lesson's promises) where values go, and **escape sequences** for what keyboards cannot type directly — **\n** for a new line, **\t** for a tab. The values follow the string in order, one per specifier: `printf("Marks: %d\n", marks);`. What the user sees — labels, spacing, new lines — is entirely the programmer's courtesy, designed here and nowhere else.
**scanf** reads the user's typed values **into variables** — and its famous peculiarity is the **&**: `scanf("%d", &age);` passes the variable's **address**, because scanf must *put* the value somewhere, not merely look at it. Forgetting the & is the C beginner's rite of passage. The book's worked whole joins the pair: read a **Celsius** temperature with scanf, compute **Fahrenheit = (C × 9/5) + 32**, print the answer with printf — input, process, output in C dress, and the template of every HSC program that follows.
