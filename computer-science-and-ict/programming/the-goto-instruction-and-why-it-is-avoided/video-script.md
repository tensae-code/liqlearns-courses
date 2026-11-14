# Video script — The Goto Instruction — and Why It Is Avoided

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **goto** instruction is written `goto <label>;` and its execution is absolute: control **transfers at once to the labelled instruction**, skipping everything between, forward or backward. With goto alone, any loop or branch can be improvised — a jump backward with an if is a loop; a jump forward is a branch. That total freedom is its seduction: goto asks no design, fits every situation, and answers to no structure.
Programs woven from free jumps earned the profession's verdict name: **spaghetti code** — control flowing like tangled strands, unreadable because a reader cannot see a jump's whole story on one page. **Structured programming** answered with the governed instructions — sequence, if, while, for, repeat, case — each with **one entry and one exit**, each readable locally. Goto survives legitimately only at rare edges (escaping several nested loops at once, in some languages without better tools). The course's rule: **know goto, recognise it, and write without it**.
