# Type Conversions in C++

## Do it first

A C++-only section of the dual course — because C++ converts where Pascal refuses. Mixing types in an expression forces the question: who becomes what, and what is lost on the way?

## Sub lesson 1 — Implicit conversion — the compiler's quiet road

In a mixed expression, C++ **converts implicitly**: an int beside a double is **widened** to double before the operation (5 + 2.0 is 7.0), and a char promotes to its code as int. The dangerous direction is the reverse, done just as quietly in an assignment: a double stored into an int is **narrowed — its fraction is cut off**, 7.9 becoming 7, with no error and no warning at default settings. Widening keeps information; narrowing destroys it — silently.

In your mind's eye: implicit conversion — the compiler's quiet road.

## Sub lesson 2 — Explicit conversion — the cast, the programmer's signature

A conversion the programmer orders is written as a **cast**: `(double) n` or `double(n)` — making n be read as a double for this operation, so n / 2 with n = 7 gives 3.5 instead of 3. The cast's virtue is **visibility**: it signs the conversion in the text, telling every reader (and the examiner) that the type change is intended, and where. The section's rule gathers both roads: let widening happen; **cast every narrowing you mean; never let a narrowing happen unmeant**.

In your mind's eye: explicit conversion — the cast, the programmer's signature.

## Say it to your companion

Tell your companion, in your own words: In a mixed expression, C++ **converts implicitly**: an int beside a double is **widened** to double before the operation (5 + 2.0 is 7.0), and a char promotes to its code as int. The dangerous direction is the reverse, done just as quietly in an assignment: a double stored into an int is **narrowed — its fraction is cut off**, 7.9 becoming 7, with no error and no warning at default settings. Widening keeps information; narrowing destroys it — silently. A conversion the programmer orders is written as a **cast**: `(double) n` or `double(n)` — making n be read as a double for this operation, so n / 2 with n = 7 gives 3.5 instead of 3. The cast's virtue is **visibility**: it signs the conversion in the text, telling every reader (and the examiner) that the type change is intended, and where. The section's rule gathers both roads: let widening happen; **cast every narrowing you mean; never let a narrowing happen unmeant**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It is widened to double before the operation — 5 + 2.0 = 7.0. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: An int — its code number. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Narrowing — the fraction is cut off: 7.9 becomes 7. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Widening; narrowing destroys it — silently. Do this with a real example of your own and write or say how you know it is right.
