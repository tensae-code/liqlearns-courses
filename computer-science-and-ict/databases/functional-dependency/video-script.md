# Video script — Functional Dependency

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Attribute **B functionally depends on A** — written **A → B** — when each value of A is always paired with **exactly one** value of B: knowing A settles B. A pupil's ID settles her name (PupilID → PupilName): two records with the same ID cannot carry two different names. But PupilName does not settle PupilID — two pupils can share a name. Dependency is **one-directional** and it is a claim about the **meaning** of the data, not about the records that happen to be present today.
Dependencies are **found** by testing pairs with the meaning test: 'if I know this, do I always know that?' — checked against the world's rules (an ISBN settles a book's title; a book's title settles nothing). A table's dependencies are listed in full before normalisation begins, because normalisation is nothing but acting on them: where a non-key attribute depends on **part** of a key, or on **another non-key attribute**, the design carries a fault the dependencies have already named. The arrow list is the diagnosis; normalisation is the cure.
