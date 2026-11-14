# Video script — Arrays in C — Holding Many Values of One Type

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **array** holds **many values of one type** under **one name**: `int marks[30];` declares thirty int rooms. It may be **initialised** at birth with a list — `int days[7] = {31, 28, 31, 30, 31, 30, 31};` — and its size is fixed at declaration: C arrays do not grow. The type rule is strict — every room holds the array's one type — which is the array's bargain: order and speed in exchange for sameness.
Rooms are reached by **index**: `marks[0]` is the **first** room, `marks[29]` the thirtieth and last — C counts from **zero**, so the last index is always **size − 1**. The loop and the array are made for each other: a for loop walking i from 0 to size−1 visits every room exactly once, which is how arrays are filled, summed and searched (the linear-search placement's home ground). The edge is unforgiving: C does **not check** an index — `marks[30]` reaches into memory that is not yours and reads or writes a stranger's value silently. The boundary is the programmer's own discipline: the loop's condition is the fence, and it must be written like one.
