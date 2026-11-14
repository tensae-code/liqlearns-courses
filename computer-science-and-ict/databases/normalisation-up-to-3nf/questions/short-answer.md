# Normalisation up to 3NF — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What may 0NF data hold?**
**Answer: Repeating groups — Subject1, Subject2, Subject3, or several facts in one cell**

**2. (Sub lesson 1) What does 1NF require?**
**Answer: Atomic values — one fact per cell — and a key identifying every record**

**3. (Sub lesson 1) How is a repeating group removed?**
**Answer: Each repeated fact gets its own record — one record per pupil–subject pair**

**4. (Sub lesson 1) What is 1NF's gain?**
**Answer: Addressability — every fact can be found, counted and updated on its own**

**5. (Sub lesson 1) When does 2NF act?**
**Answer: When the key is composite**

**6. (Sub lesson 2) What does 2NF require?**
**Answer: Every non-key attribute depends on the whole key, not part of it**

**7. (Sub lesson 2) A pupil's name in an enrolment table keyed by PupilID+Subject breaks which form?**
**Answer: 2NF — the name depends on part of the key**

**8. (Sub lesson 2) What does 3NF remove?**
**Answer: Transitive dependency — a non-key attribute depending on another non-key attribute**

**9. (Sub lesson 2) A teacher's room stored on pupil records breaks which form?**
**Answer: 3NF — the room depends on the teacher, not the pupil**

**10. (Sub lesson 2) At 3NF, where does each fact live?**
**Answer: In exactly one table — updates touch one place**

