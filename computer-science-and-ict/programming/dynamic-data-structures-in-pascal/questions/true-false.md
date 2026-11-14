# Dynamic Data Structures in Pascal — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: The address of a value in memory, not the value**
**Answer: True**

**2. (Sub lesson 1) True or false: The address of a value in memory, not the value** — as the answer to: What do new and dispose do?
**Answer: False — new reserves a fresh cell and points at it; dispose frees the cell**

**3. (Sub lesson 1) True or false: The value at the pointer's address — the dereferenced pointer**
**Answer: True**

**4. (Sub lesson 1) True or false: The value at the pointer's address — the dereferenced pointer** — as the answer to: What is nil?
**Answer: False — The pointer that points nowhere — the honest empty**

**5. (Sub lesson 1) True or false: Only through its pointer — it has no name of its own**
**Answer: True**

**6. (Sub lesson 2) True or false: Only through its pointer — it has no name of its own** — as the answer to: What is a linked list node?
**Answer: False — A record holding a value and a pointer to the next node**

**7. (Sub lesson 2) True or false: By new for an inserted node, by dispose for a removed one**
**Answer: True**

**8. (Sub lesson 2) True or false: By new for an inserted node, by dispose for a removed one** — as the answer to: What can an array not do that a list can?
**Answer: False — Fit its memory exactly to its data at run time — neither wasting nor overflowing a declared size**

**9. (Sub lesson 2) True or false: No index — the fifth node is reached by walking four links**
**Answer: True**

**10. (Sub lesson 2) True or false: No index — the fifth node is reached by walking four links** — as the answer to: What are the two housekeeping sins?
**Answer: False — Leaking (a lost pointer keeps its cell forever) and following a disposed pointer (a crash)**
