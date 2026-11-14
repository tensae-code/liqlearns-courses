# Video script — Searching an Array

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Linear search** looks for a value by walking the array **in order**, testing each element against the wanted value. Its report is kept in the **found-index variable**: the position where the value was found, or the agreed sign — nothing found — when the walk ends without a match. The two outcomes are equally the search's duty: 'it stands at place 7' and 'it is not here' are both knowledge, and a search that can only say the first is unfinished. The book's programs ask the array real questions — is this mark present, where does this name stand — and the found-index is the answer's shape.
The first version walks on even after success, finishing the array out of habit. The **improvement** is one decision: **stop at the first match** — the moment the found-index is set, the walk ends. The saving is real (on average half the array unwalked) and the lesson inside it is larger: an algorithm is **improvable** — the correct first version is a floor, not a ceiling, and the programmer's craft includes returning to working code with a colder eye. Mongolia pairs the two array lessons deliberately: sorting made the array orderly, searching makes it answerable — and both were taught as methods to be understood, traced and improved, not incantations to be memorised.
