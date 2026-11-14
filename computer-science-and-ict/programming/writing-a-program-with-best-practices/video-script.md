# Video script — Writing a Program with Best Practices

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Best practice begins at the keyboard: **meaningful names** (totalMark, not x2) that say what a thing is for; **comments** that explain **why** a part exists and what a non-obvious step does — not a narration of what the code plainly says; and **constants named** for fixed values, so no unexplained numbers (50, 0.1) wander the code. A program written this way explains itself to its next reader — who is often its writer, months later, at the moment something must change.
The second family is **shape**: **indentation** that mirrors nesting, so a loop's body and a branch's arms can be seen at a glance; **one structure per job** — sequences straight, selections and loops in their standard shapes, no jumps that tangle the flow; and development in the chapter's own order — algorithm first, code translated from it, tests planned and run. Malaysia's standard is a **production** standard: the delivered program is the one that passes its tests **and** can be handed to another programmer without an apology or a tour.
