# Video script — Normalisation up to 3NF

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Data in **0NF** (unnormalised) may hold **repeating groups**: a pupil record listing Subject1, Subject2, Subject3, or one cell holding 'Maths, English' together. **First normal form (1NF)** requires **atomic values** — each cell holds **one** fact, never a list — and the repeating group is removed by giving each repeated fact **its own record** (one record per pupil–subject pair), with a key that identifies every record. 1NF's gain is addressability: every fact can now be found, counted and updated on its own.
**Second normal form (2NF)** acts when the key is **composite**: every non-key attribute must depend on the **whole key**, not on **part** of it (a pupil's name depends only on PupilID, not on the PupilID+Subject pair — so names leave the enrolment table for the pupil table). **Third normal form (3NF)** removes **transitive dependency**: a non-key attribute must not depend on **another non-key attribute** (a teacher's room depends on the teacher, not on the pupil — so it leaves for the teacher table). At 3NF each fact lives in exactly one table, updates touch one place, and the design is what Malaysia calls ternormal — normalised.
