# Video script — Python Tuples — Immutable Sequences

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **tuple** holds values **in order**, like a list — but written in **round brackets** and **immutable**: after creation, no item can be changed, added or removed. Indexing and counting work as they did for lists, so reading a tuple is familiar; only the writing is forbidden. An attempt to change one is an error the program raises, not a quiet failure — Python defends the tuple's fixedness loudly.
Immutability is a **feature chosen on purpose**: a tuple holds data that **must not change** while the program runs — the days of the week, a point's coordinates (x, y), a record's fixed fields — where an accidental change would be a bug the program could not see. The course's rule of choice: a **list** for a collection the program will **build and change**; a **tuple** for a collection whose changing would be a **mistake**. Same order, same indexing — opposite promises.
