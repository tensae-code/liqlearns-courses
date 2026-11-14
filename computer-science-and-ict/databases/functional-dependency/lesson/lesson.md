# Functional Dependency

## Do it first

Normalisation has a tool, and this is it. Malaysia teaches functional dependency first: a way of saying, exactly, which values settle which other values in a table. In this lesson you learn to find dependencies and write them with the arrow.

## Sub lesson 1 — The arrow — A settles B

Attribute **B functionally depends on A** — written **A → B** — when each value of A is always paired with **exactly one** value of B: knowing A settles B. A pupil's ID settles her name (PupilID → PupilName): two records with the same ID cannot carry two different names. But PupilName does not settle PupilID — two pupils can share a name. Dependency is **one-directional** and it is a claim about the **meaning** of the data, not about the records that happen to be present today.

[Picture — The arrow — A settles B]

## Sub lesson 2 — Finding and using dependencies

Dependencies are **found** by testing pairs with the meaning test: 'if I know this, do I always know that?' — checked against the world's rules (an ISBN settles a book's title; a book's title settles nothing). A table's dependencies are listed in full before normalisation begins, because normalisation is nothing but acting on them: where a non-key attribute depends on **part** of a key, or on **another non-key attribute**, the design carries a fault the dependencies have already named. The arrow list is the diagnosis; normalisation is the cure.

[Picture — Finding and using dependencies]

## Say it to your companion

Tell your companion, in your own words: Attribute **B functionally depends on A** — written **A → B** — when each value of A is always paired with **exactly one** value of B: knowing A settles B. A pupil's ID settles her name (PupilID → PupilName): two records with the same ID cannot carry two different names. But PupilName does not settle PupilID — two pupils can share a name. Dependency is **one-directional** and it is a claim about the **meaning** of the data, not about the records that happen to be present today. Dependencies are **found** by testing pairs with the meaning test: 'if I know this, do I always know that?' — checked against the world's rules (an ISBN settles a book's title; a book's title settles nothing). A table's dependencies are listed in full before normalisation begins, because normalisation is nothing but acting on them: where a non-key attribute depends on **part** of a key, or on **another non-key attribute**, the design carries a fault the dependencies have already named. The arrow list is the diagnosis; normalisation is the cure. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: B functionally depends on A — each value of A is paired with exactly one value of B. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Knowing A settles B. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — two pupils can share a name; dependency is one-directional. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: By the meaning test: 'if I know this, do I always know that?'. Do this with a real example of your own and write or say how you know it is right.
