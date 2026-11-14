# Functional Dependency — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "What does A → B mean?" is: B functionally depends on A — each value of A is paired with exactly one value of B**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "In plain words, what does dependency say?" is: No — two pupils can share a name; dependency is one-directional**
**Answer: False** — Knowing A settles B

**3. (Sub lesson 1) True or false: the answer to "PupilID → PupilName holds. Does PupilName → PupilID?" is: No — two pupils can share a name; dependency is one-directional**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "Is dependency about today's records or the data's meaning?" is: ISBN → BookTitle — an ISBN settles a book's title**
**Answer: False** — The meaning — it must hold always, not just in the records present

**5. (Sub lesson 1) True or false: the answer to "Give another true dependency." is: ISBN → BookTitle — an ISBN settles a book's title**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "How are dependencies found?" is: In full, before normalisation begins**
**Answer: False** — By the meaning test: 'if I know this, do I always know that?'

**7. (Sub lesson 2) True or false: the answer to "When are a table's dependencies listed?" is: In full, before normalisation begins**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "What is normalisation, on this view?" is: A non-key attribute depending on part of a key, or on another non-key attribute**
**Answer: False** — Acting on the dependencies

**9. (Sub lesson 2) True or false: the answer to "Name a fault the dependencies expose." is: A non-key attribute depending on part of a key, or on another non-key attribute**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "The arrow list is the diagnosis; normalisation is what?" is: B functionally depends on A — each value of A is paired with exactly one value of B**
**Answer: False** — The cure

