# The Goto Instruction — and Why It Is Avoided

## Do it first

Grade 10's instruction set ends with its cautionary exhibit. Goto does one thing perfectly — jumps — and that one thing, used freely, is exactly what a program must not do.

## Sub lesson 1 — goto — the unconditional jump

The **goto** instruction is written `goto <label>;` and its execution is absolute: control **transfers at once to the labelled instruction**, skipping everything between, forward or backward. With goto alone, any loop or branch can be improvised — a jump backward with an if is a loop; a jump forward is a branch. That total freedom is its seduction: goto asks no design, fits every situation, and answers to no structure.

In your mind's eye: goto — the unconditional jump.

[Picture 47838 — goto — the unconditional jump]

## Sub lesson 2 — Why it is avoided — spaghetti and structure

Programs woven from free jumps earned the profession's verdict name: **spaghetti code** — control flowing like tangled strands, unreadable because a reader cannot see a jump's whole story on one page. **Structured programming** answered with the governed instructions — sequence, if, while, for, repeat, case — each with **one entry and one exit**, each readable locally. Goto survives legitimately only at rare edges (escaping several nested loops at once, in some languages without better tools). The course's rule: **know goto, recognise it, and write without it**.

In your mind's eye: why it is avoided — spaghetti and structure.

[Picture 47839 — why it is avoided — spaghetti and structure]

## Say it to your companion

Tell your companion, in your own words: The **goto** instruction is written `goto <label>;` and its execution is absolute: control **transfers at once to the labelled instruction**, skipping everything between, forward or backward. With goto alone, any loop or branch can be improvised — a jump backward with an if is a loop; a jump forward is a branch. That total freedom is its seduction: goto asks no design, fits every situation, and answers to no structure. Programs woven from free jumps earned the profession's verdict name: **spaghetti code** — control flowing like tangled strands, unreadable because a reader cannot see a jump's whole story on one page. **Structured programming** answered with the governed instructions — sequence, if, while, for, repeat, case — each with **one entry and one exit**, each readable locally. Goto survives legitimately only at rare edges (escaping several nested loops at once, in some languages without better tools). The course's rule: **know goto, recognise it, and write without it**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It transfers control at once to the labelled instruction, skipping everything between. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Yes — forward (a branch) or backward (a loop, with an if). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Any loop or branch. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Total freedom — it asks no design and fits every situation. Do this with a real example of your own and write or say how you know it is right.
