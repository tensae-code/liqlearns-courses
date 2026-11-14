# Video script — switch — Multiple-Way Selection

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**switch (n) { case 1: … }** compares **n** once against each **case** constant. On a match, that case's statements run. switch suits selections driven by **one value with many named possibilities** — menu choices, day numbers, grade letters — where an if-elif chain would repeat the same test clumsily.
Without **break**, execution **falls through**: the matched case runs, then the **next** case runs too, and so on — occasionally wanted, usually a bug. **default** is the case for **everything else**, the switch's else, catching values the writer did not name. The book adds a full **exercises** section (§3.26) after the structure (§3.25): trace each exercise by naming the matched case and every statement that runs before a break stops it.
