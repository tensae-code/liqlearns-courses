# Dynamic Data Structures in Pascal — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) What does a pointer hold?** → **The address of a value in memory, not the value**

**2. (Sub lesson 1) What do new and dispose do?** → **new reserves a fresh cell and points at it; dispose frees the cell**

**3. (Sub lesson 1) What does p^ name?** → **The value at the pointer's address — the dereferenced pointer**

**4. (Sub lesson 1) What is nil?** → **The pointer that points nowhere — the honest empty**

**5. (Sub lesson 1) How is a new-made variable reached?** → **Only through its pointer — it has no name of its own**

**6. (Sub lesson 2) What is a linked list node?** → **A record holding a value and a pointer to the next node**

**7. (Sub lesson 2) How does a list grow and shrink?** → **By new for an inserted node, by dispose for a removed one**

**8. (Sub lesson 2) What can an array not do that a list can?** → **Fit its memory exactly to its data at run time — neither wasting nor overflowing a declared size**

**9. (Sub lesson 2) What is a list's price in access?** → **No index — the fifth node is reached by walking four links**

**10. (Sub lesson 2) What are the two housekeeping sins?** → **Leaking (a lost pointer keeps its cell forever) and following a disposed pointer (a crash)**
