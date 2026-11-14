# Video script — Labels in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **label** is a **mark attached to an instruction**, written before it and separated by a colon: `10: writeln(x);`. In Pascal, labels are **unsigned integer constants** (or identifiers where dialects allow) and must be **declared** in a `label` declaration before use; in C++, labels are **identifiers** needing no declaration. A label has no value and does no work: it is an address in the text, a place other instructions can name — built entirely for the goto instruction that §3.17 will judge.
Labels belong to the vocabulary because the grammar includes them, but the course's posture is the profession's: **structured instructions (if, while, for, repeat) have made labels nearly unnecessary** — every honest loop and branch has its structured form, which reads in order. The labelled jump survives at the edges (leaving deep nests at once, machine-generated code). Learning labels is learning to *recognise* them — and to know why the programs in this course almost never wear one.
