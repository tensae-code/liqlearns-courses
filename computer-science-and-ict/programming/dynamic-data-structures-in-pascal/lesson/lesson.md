# Dynamic Data Structures in Pascal

## Do it first

Every structure so far declared its size before it ran. The first Grade 12 programming elective removes that limit: structures that grow and shrink while the program runs, built from pointers.

## Sub lesson 1 — Pointers — variables that hold addresses

A **pointer** is a variable that holds not a value but the **address of a value** in memory: `var p: ^integer;` declares a pointer to an integer. The operations are a small new alphabet: **new(p)** reserves a fresh cell and sets p to its address; **p^** names the value at the address (the pointer **dereferenced**); **dispose(p)** frees the cell; **nil** is the pointer that points nowhere — the honest empty. A variable made by new has **no name of its own**: it is reached only through its pointer, which is the structure's whole new power and danger.

In your mind's eye: pointers — variables that hold addresses.

[Picture 47056 — pointers — variables that hold addresses]

## Sub lesson 2 — Linked lists — structure built at run time

A **linked list** chains **nodes** — records holding a value and a **pointer to the next node** — ending at nil. It **grows by one new per inserted node and shrinks by dispose**, needing exactly the memory its data needs, where an array wastes its declared size or overflows it. Its prices are the duals of its gifts: no index (the fifth node is reached by **walking** four links), and the programmer now owns memory's housekeeping — a lost pointer **leaks** its cell, a followed disposed pointer **crashes**. Dynamic structures trade the compiler's guard for the programmer's freedom, knowingly.

In your mind's eye: linked lists — structure built at run time.

[Picture 47057 — linked lists — structure built at run time]

## Say it to your companion

Tell your companion, in your own words: A **pointer** is a variable that holds not a value but the **address of a value** in memory: `var p: ^integer;` declares a pointer to an integer. The operations are a small new alphabet: **new(p)** reserves a fresh cell and sets p to its address; **p^** names the value at the address (the pointer **dereferenced**); **dispose(p)** frees the cell; **nil** is the pointer that points nowhere — the honest empty. A variable made by new has **no name of its own**: it is reached only through its pointer, which is the structure's whole new power and danger. A **linked list** chains **nodes** — records holding a value and a **pointer to the next node** — ending at nil. It **grows by one new per inserted node and shrinks by dispose**, needing exactly the memory its data needs, where an array wastes its declared size or overflows it. Its prices are the duals of its gifts: no index (the fifth node is reached by **walking** four links), and the programmer now owns memory's housekeeping — a lost pointer **leaks** its cell, a followed disposed pointer **crashes**. Dynamic structures trade the compiler's guard for the programmer's freedom, knowingly. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The address of a value in memory, not the value. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: new reserves a fresh cell and points at it; dispose frees the cell. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The value at the pointer's address — the dereferenced pointer. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The pointer that points nowhere — the honest empty. Do this with a real example of your own and write or say how you know it is right.
