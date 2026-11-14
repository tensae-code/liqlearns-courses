# Video script — Python Lists — Creating, Indexing and Methods

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **list** holds **many values in one variable, in order**, written in square brackets: `marks = [18, 15, 20]`. Each item has an **index** — its position counted **from 0** — and `marks[1]` reaches the second item. Indexing is the list's promise: any item can be reached directly by its number, changed by assignment to its index, and counted with `len()`. The course begins here because almost every real program's data arrives as a collection, not a lone value.
Lists are **mutable** — they can change after creation — and their **methods** are the changes with names: **append** adds an item at the end; **insert** places one at a chosen index; **remove** and **pop** take items out; **sort** orders them and **reverse** turns them around; **index** and **count** answer questions about what is inside. Read a method by its effect on the collection, and remember the course's warning in the same breath: the list changed is the same list — no copy is made unless the program asks for one.
