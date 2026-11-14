# Video script — Operator Precedence and Associativity in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Precedence** ranks the operators: brackets first, then powers, then multiplication and division, then addition and subtraction; comparisons and logic sit lower in their own ranks. An expression is worked out by precedence, not by reading order — `2 + 3 * 4` is 14 because the multiplication outranks the addition. Jordan's Python lesson teaches the ladder with the standing advice attached: when the order matters to a reader, **brackets** say it — precedence is for reading code, brackets are for writing it kindly.
Operators of **equal precedence** are settled by **associativity**: most work **left to right** (`10 - 4 - 3` = (10−4)−3 = 3), but the power operator works **right to left** (`2 ** 3 ** 2` = 2^(3^2) = 512, not 64). Assignment, too, associates right to left. The pair of rules together — precedence for rank, associativity for ties — decide every expression Python will ever meet, which is why the book drills them before the conditionals that spend them.
