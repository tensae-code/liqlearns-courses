# Normalisation up to 3NF

## Do it first

One big table with everything in it is where database trouble lives: repeated groups, half-known facts, updates that miss copies. Malaysia teaches the cure as a staircase of normal forms. In this lesson you climb 0NF to 3NF, one fault removed per step.

## Sub lesson 1 — 0NF to 1NF — atomic values, one fact per cell

Data in **0NF** (unnormalised) may hold **repeating groups**: a pupil record listing Subject1, Subject2, Subject3, or one cell holding 'Maths, English' together. **First normal form (1NF)** requires **atomic values** — each cell holds **one** fact, never a list — and the repeating group is removed by giving each repeated fact **its own record** (one record per pupil–subject pair), with a key that identifies every record. 1NF's gain is addressability: every fact can now be found, counted and updated on its own.

In your mind's eye: 0NF to 1NF — atomic values, one fact per cell.

[Picture 46564 — 0NF to 1NF — atomic values, one fact per cell]

## Sub lesson 2 — 2NF and 3NF — dependencies put in their own tables

**Second normal form (2NF)** acts when the key is **composite**: every non-key attribute must depend on the **whole key**, not on **part** of it (a pupil's name depends only on PupilID, not on the PupilID+Subject pair — so names leave the enrolment table for the pupil table). **Third normal form (3NF)** removes **transitive dependency**: a non-key attribute must not depend on **another non-key attribute** (a teacher's room depends on the teacher, not on the pupil — so it leaves for the teacher table). At 3NF each fact lives in exactly one table, updates touch one place, and the design is what Malaysia calls ternormal — normalised.

In your mind's eye: 2NF and 3NF — dependencies put in their own tables.

[Picture 46565 — 2NF and 3NF — dependencies put in their own tables]

## Say it to your companion

Tell your companion, in your own words: Data in **0NF** (unnormalised) may hold **repeating groups**: a pupil record listing Subject1, Subject2, Subject3, or one cell holding 'Maths, English' together. **First normal form (1NF)** requires **atomic values** — each cell holds **one** fact, never a list — and the repeating group is removed by giving each repeated fact **its own record** (one record per pupil–subject pair), with a key that identifies every record. 1NF's gain is addressability: every fact can now be found, counted and updated on its own. **Second normal form (2NF)** acts when the key is **composite**: every non-key attribute must depend on the **whole key**, not on **part** of it (a pupil's name depends only on PupilID, not on the PupilID+Subject pair — so names leave the enrolment table for the pupil table). **Third normal form (3NF)** removes **transitive dependency**: a non-key attribute must not depend on **another non-key attribute** (a teacher's room depends on the teacher, not on the pupil — so it leaves for the teacher table). At 3NF each fact lives in exactly one table, updates touch one place, and the design is what Malaysia calls ternormal — normalised. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Repeating groups — Subject1, Subject2, Subject3, or several facts in one cell. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Atomic values — one fact per cell — and a key identifying every record. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Each repeated fact gets its own record — one record per pupil–subject pair. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Every non-key attribute depends on the whole key, not part of it. Do this with a real example of your own and write or say how you know it is right.
