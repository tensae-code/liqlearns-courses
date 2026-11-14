# Video script — Separators in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Separators** divide program text into its units: **blanks and line breaks** separate words; **commas** separate lists (parameters, values); **brackets** group; and the **semicolon** separates — in Pascal, instructions from each other; in C++, it **ends** each instruction as its terminator. The compiler reads separators before meaning: two programs with the same words and different separators are different programs, or one is no program at all. Whitespace beyond separation is free — indentation is written for people, paid for by nobody.
The semicolon is the pair's emblematic difference. In **Pascal**, because it separates, the last instruction before **end** needs none — and an extra one only plants an empty instruction. In **C++**, because it terminates, a missing semicolon is an immediate error, and an extra one is an **empty statement** with the same traps (the stray `if (x>0);`). Reading separators is reading grammar: the same text, cut differently by the two languages, means differently — the vocabulary chapter's last proof that syntax is real.
