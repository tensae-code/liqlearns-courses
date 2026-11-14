# Video script — Character Arrays and Searching

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**char word[10] = "Skopje";** stores the letters in elements 0–5 and then the **null terminator '\0'** in element 6 — the mark every text routine watches for. The array's declared size is its **capacity**; the text's **length** is the count up to the terminator, which a simple walk can measure. Spaces are characters too and take elements of their own.
**Searching** walks the array comparing each element with the target: stop with **found** (and its position) on a match, or stop at the **terminator** with not-found. The same walk counts occurrences (do not stop at the first match — count and continue) or tests membership. Case matters: 'A' and 'a' are different characters with different codes, so searches must say which they mean.
