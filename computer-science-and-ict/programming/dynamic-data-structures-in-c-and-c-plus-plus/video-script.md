# Video script — Dynamic Data Structures in C and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

C++ reserves run-time memory with **new** — `int* p = new int;` — which returns the **address** of a fresh cell, and returns it with **delete**. The pointed value is reached as **\*p**. Arrays can be born dynamic too (`new int[n]` with n known only at run time — the array whose size the program itself decides), freed by **delete[]**. Every new is a **loan**: the memory is the system's, held until delete — the contract whose breaches the next part names.
Manual memory's three classic wounds: the **memory leak** (a pointer overwritten before delete — its cell lost for the run's whole life), the **dangling pointer** (delete done, pointer kept and followed into freed memory now possibly reused), and the **wild pointer** (never set at all, followed anywhere). Pascal fences some of this (typed pointers, no pointer arithmetic); C++ allows **pointer arithmetic** itself (p + 1 steps to the next cell) — power for arrays' innards, and rope. The elective's rule closes the pair's programming theory: **every new pairs with a delete, every pointer is nil-or-valid, and a freed pointer is set to nullptr at once**.
