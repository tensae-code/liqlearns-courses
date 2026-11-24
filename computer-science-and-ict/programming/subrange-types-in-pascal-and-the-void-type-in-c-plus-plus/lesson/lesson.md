# Subrange Types in Pascal — and the void Type in C++

## Do it first

Grade 10's types chapter pairs two extremes in one sitting: the type that holds *fewer* values than any other, and the type that holds *none*. Together they close the map of what a type can be.

## Sub lesson 1 — The subrange — Pascal's guarded slice

The **subrange** (met in Grade 7) is a slice of an ordinal host: `1..31`, `'A'..'Z'`, `Mon..Fri` — a variable holds only values inside the slice, and range checking **stops the program at a violating assignment**. C++ has **no subrange type**: the same honesty must be written by hand, as checks inside the program — the concept survives, the guard changes from the type system to the programmer's discipline. The comparison is the point: what one language enforces, the other must remember.

In your mind's eye: the subrange — Pascal's guarded slice.

## Sub lesson 2 — void — the type of no value

C++'s **void** names the **absence of a value**: a function declared void **returns nothing** — it is C++'s spelling of Pascal's **procedure**, against value-returning functions. No variable can be of type void; nothing is stored, compared or printed. Its lesson is symmetry's: a type system needs a word not only for every kind of value but for **no value**, so that 'this subprogram only acts' is said in the type itself. Pascal says it with a keyword (procedure), C++ with a type (void) — the pair's neat parting difference.

In your mind's eye: void — the type of no value.

## Say it to your companion

Tell your companion, in your own words: The **subrange** (met in Grade 7) is a slice of an ordinal host: `1..31`, `'A'..'Z'`, `Mon..Fri` — a variable holds only values inside the slice, and range checking **stops the program at a violating assignment**. C++ has **no subrange type**: the same honesty must be written by hand, as checks inside the program — the concept survives, the guard changes from the type system to the programmer's discipline. The comparison is the point: what one language enforces, the other must remember. C++'s **void** names the **absence of a value**: a function declared void **returns nothing** — it is C++'s spelling of Pascal's **procedure**, against value-returning functions. No variable can be of type void; nothing is stored, compared or printed. Its lesson is symmetry's: a type system needs a word not only for every kind of value but for **no value**, so that 'this subprogram only acts' is said in the type itself. Pascal says it with a keyword (procedure), C++ with a type (void) — the pair's neat parting difference. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A slice of an ordinal host type, holding only values inside it. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Range checking — an error at that line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — the same honesty is written as checks by hand. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The guard — from the type system to the programmer's discipline. Do this with a real example of your own and write or say how you know it is right.
