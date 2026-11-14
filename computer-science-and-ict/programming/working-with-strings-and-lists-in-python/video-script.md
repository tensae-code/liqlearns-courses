# Video script — Working with Strings and Lists in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **string** is worked on, not just printed. Its **length** is counted with `len`; a **slice** cuts out a run of characters by their positions; **joining** (concatenation) builds a longer string from parts; and methods reshape it — upper and lower case, finding where a piece occurs, replacing one piece with another. Two rules guard all of it: positions count **from zero**, and a string itself never changes — every operation returns a **new** string, so the result must be kept if it is wanted. Egypt pairs strings with lists in one lesson because Python treats them as cousins: both are sequences, counted, sliced and looped the same way.
A **list**, unlike a string, can be **changed in place**: items are **appended** at the end, **inserted** at a position, **removed** by value or position, and the whole list can be **sorted** or **reversed**. Finding is the other daily job — whether an item is **in** the list, and at which **index** it stands. The operations compose: a mark list is appended to all term, sorted for the report, searched for one pupil, sliced for the top five. The faults are the family's too: removing while looping skips items, and sorting text-numbers orders them as words, not values — two traps the book's exercises make pupils meet on small lists before real ones.
