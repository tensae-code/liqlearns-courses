# Video script — Syntax Diagrams

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In a **syntax diagram**, each construction has its own named chart. **Terminal symbols** stand in **round-ended boxes** — they are written exactly as shown; **nonterminals** stand in **rectangular boxes** — they send you to their own charts. You read by **following the arrows**: whatever sequence of boxes a complete path collects, in order, is a legal form of the construction. Where arrows **branch**, the grammar offers a choice; where an arrow **loops back**, the part may repeat.
Diagrams and BNF describe **the same grammar** in two media: every production becomes a chart, every chart reads back into productions. Diagrams show **flow** better (a loop is seen at a glance); BNF is **shorter to write** and easier to print and search. The languages' manuals use both, so the course teaches both: the pupil who can translate a rule between the two truly owns it — as with Pascal and C++, the concept survives its clothing.
