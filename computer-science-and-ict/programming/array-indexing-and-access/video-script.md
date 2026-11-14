# Video script — Array Indexing and Access

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**a[0]** is the **first** element, a[1] the second, and **a[n−1]** the **last** in an array of size n. The **index** (subscript) is written in square brackets and can be any integer expression — a literal, a variable, even a calculation — which is what makes loops over arrays possible: for (i = 0; i < n; i++) visits each element exactly once.
**a[n]** does not exist: it names memory **past the array**, and C++ performs **no bounds checking** — reading it gives garbage, writing it damages whatever lives there, and the program may crash later somewhere unrelated. Keeping the loop condition **i < n** (never i <= n) is the standing guard. Off-by-one at the array's edge is the classic array bug.
