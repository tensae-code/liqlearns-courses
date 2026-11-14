# Normalisation up to 3NF — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "What may 0NF data hold?" is: Repeating groups — Subject1, Subject2, Subject3, or several facts in one cell**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "What does 1NF require?" is: Each repeated fact gets its own record — one record per pupil–subject pair**
**Answer: False** — Atomic values — one fact per cell — and a key identifying every record

**3. (Sub lesson 1) True or false: the answer to "How is a repeating group removed?" is: Each repeated fact gets its own record — one record per pupil–subject pair**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "What is 1NF's gain?" is: When the key is composite**
**Answer: False** — Addressability — every fact can be found, counted and updated on its own

**5. (Sub lesson 1) True or false: the answer to "When does 2NF act?" is: When the key is composite**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "What does 2NF require?" is: 2NF — the name depends on part of the key**
**Answer: False** — Every non-key attribute depends on the whole key, not part of it

**7. (Sub lesson 2) True or false: the answer to "A pupil's name in an enrolment table keyed by PupilID+Subject breaks which form?" is: 2NF — the name depends on part of the key**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "What does 3NF remove?" is: 3NF — the room depends on the teacher, not the pupil**
**Answer: False** — Transitive dependency — a non-key attribute depending on another non-key attribute

**9. (Sub lesson 2) True or false: the answer to "A teacher's room stored on pupil records breaks which form?" is: 3NF — the room depends on the teacher, not the pupil**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "At 3NF, where does each fact live?" is: Repeating groups — Subject1, Subject2, Subject3, or several facts in one cell**
**Answer: False** — In exactly one table — updates touch one place

