# Video script — Abstract Data Types

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **abstract data type** defines a kind of data by its **operations and their behaviour** — what you may do with it and what each doing guarantees — while **hiding how** it is stored and built. A stack ADT says: push, pop, peek — pop returns the last pushed. Whether the stack is a list, an array or a chain inside is **not the user's business**. The definition is a contract: behaviour promised, machinery private.
The gains repeat the car's: **use without building** (any program may use a stack without reinventing it), **change without breakage** (the inside can be rebuilt faster while the contract holds, and no user notices), and **thinking at the right level** (the algorithm is designed in pushes and pops, not in memory cells). Jordan's Grade 12 lesson names the idea after the concrete structures (lists, tuples, dictionaries, sets) on purpose: an ADT is what those structures are *instances* of thinking about — Python's list is one maker's answer to the sequence ADT's contract.
