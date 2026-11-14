# Functional Dependency — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does A → B mean?**
**Answer: B functionally depends on A — each value of A is paired with exactly one value of B**

**2. (Sub lesson 1) In plain words, what does dependency say?**
**Answer: Knowing A settles B**

**3. (Sub lesson 1) PupilID → PupilName holds. Does PupilName → PupilID?**
**Answer: No — two pupils can share a name; dependency is one-directional**

**4. (Sub lesson 1) Is dependency about today's records or the data's meaning?**
**Answer: The meaning — it must hold always, not just in the records present**

**5. (Sub lesson 1) Give another true dependency.**
**Answer: ISBN → BookTitle — an ISBN settles a book's title**

**6. (Sub lesson 2) How are dependencies found?**
**Answer: By the meaning test: 'if I know this, do I always know that?'**

**7. (Sub lesson 2) When are a table's dependencies listed?**
**Answer: In full, before normalisation begins**

**8. (Sub lesson 2) What is normalisation, on this view?**
**Answer: Acting on the dependencies**

**9. (Sub lesson 2) Name a fault the dependencies expose.**
**Answer: A non-key attribute depending on part of a key, or on another non-key attribute**

**10. (Sub lesson 2) The arrow list is the diagnosis; normalisation is what?**
**Answer: The cure**

