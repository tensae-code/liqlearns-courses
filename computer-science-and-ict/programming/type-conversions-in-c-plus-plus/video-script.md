# Video script — Type Conversions in C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In a mixed expression, C++ **converts implicitly**: an int beside a double is **widened** to double before the operation (5 + 2.0 is 7.0), and a char promotes to its code as int. The dangerous direction is the reverse, done just as quietly in an assignment: a double stored into an int is **narrowed — its fraction is cut off**, 7.9 becoming 7, with no error and no warning at default settings. Widening keeps information; narrowing destroys it — silently.
A conversion the programmer orders is written as a **cast**: `(double) n` or `double(n)` — making n be read as a double for this operation, so n / 2 with n = 7 gives 3.5 instead of 3. The cast's virtue is **visibility**: it signs the conversion in the text, telling every reader (and the examiner) that the type change is intended, and where. The section's rule gathers both roads: let widening happen; **cast every narrowing you mean; never let a narrowing happen unmeant**.
