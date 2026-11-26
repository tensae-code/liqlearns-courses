# Dynamic Data Structures in C and C++

## Do it first

The second dynamic elective crosses the pair. C++ builds the same run-time structures — with the same pointers, and with famous traps Pascal's stricter house partly fences.

## Sub lesson 1 — new and delete — memory asked and returned

C++ reserves run-time memory with **new** — `int* p = new int;` — which returns the **address** of a fresh cell, and returns it with **delete**. The pointed value is reached as **\*p**. Arrays can be born dynamic too (`new int[n]` with n known only at run time — the array whose size the program itself decides), freed by **delete[]**. Every new is a **loan**: the memory is the system's, held until delete — the contract whose breaches the next part names.

In your mind's eye: new and delete — memory asked and returned.

[Picture 47054 — new and delete — memory asked and returned]

## Sub lesson 2 — The sharper edges — leaks, dangling and wild pointers

Manual memory's three classic wounds: the **memory leak** (a pointer overwritten before delete — its cell lost for the run's whole life), the **dangling pointer** (delete done, pointer kept and followed into freed memory now possibly reused), and the **wild pointer** (never set at all, followed anywhere). Pascal fences some of this (typed pointers, no pointer arithmetic); C++ allows **pointer arithmetic** itself (p + 1 steps to the next cell) — power for arrays' innards, and rope. The elective's rule closes the pair's programming theory: **every new pairs with a delete, every pointer is nil-or-valid, and a freed pointer is set to nullptr at once**.

In your mind's eye: the sharper edges — leaks, dangling and wild pointers.

[Picture 47055 — the sharper edges — leaks, dangling and wild pointers]

## Say it to your companion

Tell your companion, in your own words: C++ reserves run-time memory with **new** — `int* p = new int;` — which returns the **address** of a fresh cell, and returns it with **delete**. The pointed value is reached as **\*p**. Arrays can be born dynamic too (`new int[n]` with n known only at run time — the array whose size the program itself decides), freed by **delete[]**. Every new is a **loan**: the memory is the system's, held until delete — the contract whose breaches the next part names. Manual memory's three classic wounds: the **memory leak** (a pointer overwritten before delete — its cell lost for the run's whole life), the **dangling pointer** (delete done, pointer kept and followed into freed memory now possibly reused), and the **wild pointer** (never set at all, followed anywhere). Pascal fences some of this (typed pointers, no pointer arithmetic); C++ allows **pointer arithmetic** itself (p + 1 steps to the next cell) — power for arrays' innards, and rope. The elective's rule closes the pair's programming theory: **every new pairs with a delete, every pointer is nil-or-valid, and a freed pointer is set to nullptr at once**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The address of a fresh cell. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: *p — the dereferenced pointer. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Born with new int[n] — n decided at run time; freed with delete[]. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A loan — the system's memory, held until delete. Do this with a real example of your own and write or say how you know it is right.
