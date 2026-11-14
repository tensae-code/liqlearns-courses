# Video script — Subrange Types in Pascal — and the void Type in C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **subrange** (met in Grade 7) is a slice of an ordinal host: `1..31`, `'A'..'Z'`, `Mon..Fri` — a variable holds only values inside the slice, and range checking **stops the program at a violating assignment**. C++ has **no subrange type**: the same honesty must be written by hand, as checks inside the program — the concept survives, the guard changes from the type system to the programmer's discipline. The comparison is the point: what one language enforces, the other must remember.
C++'s **void** names the **absence of a value**: a function declared void **returns nothing** — it is C++'s spelling of Pascal's **procedure**, against value-returning functions. No variable can be of type void; nothing is stored, compared or printed. Its lesson is symmetry's: a type system needs a word not only for every kind of value but for **no value**, so that 'this subprogram only acts' is said in the type itself. Pascal says it with a keyword (procedure), C++ with a type (void) — the pair's neat parting difference.
