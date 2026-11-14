# Video script — Code Review With a Checklist

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Code review** is the practice of having another programmer **read code before it is accepted**, looking for faults, risks and unreadable places. The writer cannot do it alone: they read what they *meant*, not what they *wrote*. The reviewer reads what is actually there. Armenia's Grade 10 book teaches review together with its instrument (Lesson 21): 'Code review and the checklist. Checklist structure' — the review is a quality practice of the senior course, sitting between readable code and debugging.
A **checklist** makes review complete instead of impressionistic. A good checklist is **structured in sections** that follow the code's own risks: correctness (boundaries, empty cases, division by zero), readability (names, layout, style-sheet rules), safety (inputs checked, files closed), and tests (is there a test for the risky part?). Each item is a **yes/no question** answerable from the code, short enough to run in minutes, and revised when a real fault escapes — the list learns from every miss.
