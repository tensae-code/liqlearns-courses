# Video script — The Integer and int Types in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Both languages offer whole numbers in **several sizes**: Pascal's family runs from shortint and byte through **integer** to longint; C++'s from short through **int** to long. Each size fixes a **range** (2ⁿ patterns). Every size also offers an **unsigned** twin (Pascal's byte/word; C++'s unsigned int) that spends all its patterns on 0 and positives, doubling the top at the price of negatives. Choosing a whole-number type is choosing **range and sign** together — and knowing both before the data arrives.
The pair agrees on +, −, * and disagrees, instructively, on division. Pascal splits it: **/** gives a real, **div** the whole quotient, **mod** the remainder. C++'s **/** on two ints *is* Pascal's div — the whole quotient, fraction discarded — and **%** is its mod: 7 / 2 is 3 in C++ integers, 7 % 2 is 1. The same symbols, different contracts: the dual course's recurring lesson — **the type and the language together fix what an operator does**, never the symbol alone.
