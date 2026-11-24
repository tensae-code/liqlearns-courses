# Abstract Data Types

## Do it first

You can drive a car without building its engine: you know what it does, not how. This lesson learns that same separation inside data — the idea the whole data-structures lesson was walking toward.

## Sub lesson 1 — What an ADT is

An **abstract data type** defines a kind of data by its **operations and their behaviour** — what you may do with it and what each doing guarantees — while **hiding how** it is stored and built. A stack ADT says: push, pop, peek — pop returns the last pushed. Whether the stack is a list, an array or a chain inside is **not the user's business**. The definition is a contract: behaviour promised, machinery private.

In your mind's eye: what an ADT is.

## Sub lesson 2 — Why abstraction earns its place

The gains repeat the car's: **use without building** (any program may use a stack without reinventing it), **change without breakage** (the inside can be rebuilt faster while the contract holds, and no user notices), and **thinking at the right level** (the algorithm is designed in pushes and pops, not in memory cells). Jordan's Grade 12 lesson names the idea after the concrete structures (lists, tuples, dictionaries, sets) on purpose: an ADT is what those structures are *instances* of thinking about — Python's list is one maker's answer to the sequence ADT's contract.

In your mind's eye: why abstraction earns its place.

## Say it to your companion

Tell your companion, in your own words: An **abstract data type** defines a kind of data by its **operations and their behaviour** — what you may do with it and what each doing guarantees — while **hiding how** it is stored and built. A stack ADT says: push, pop, peek — pop returns the last pushed. Whether the stack is a list, an array or a chain inside is **not the user's business**. The definition is a contract: behaviour promised, machinery private. The gains repeat the car's: **use without building** (any program may use a stack without reinventing it), **change without breakage** (the inside can be rebuilt faster while the contract holds, and no user notices), and **thinking at the right level** (the algorithm is designed in pushes and pops, not in memory cells). Jordan's Grade 12 lesson names the idea after the concrete structures (lists, tuples, dictionaries, sets) on purpose: an ADT is what those structures are *instances* of thinking about — Python's list is one maker's answer to the sequence ADT's contract. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its operations and their behaviour — not how it is built. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Push, pop, peek — pop returns the last pushed. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Whether the stack is a list, array or chain inside. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A contract — behaviour promised, machinery private. Do this with a real example of your own and write or say how you know it is right.
