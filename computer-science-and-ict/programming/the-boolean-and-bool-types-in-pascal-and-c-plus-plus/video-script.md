# Video script — The Boolean and bool Types in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Pascal's **boolean** and C++'s **bool** hold the same two values — Pascal writes **true/false**, C++ writes **true/false** as keywords too. Both are born mainly from **comparisons** (a > b, x == y — note C++'s double equals for comparison against its single = for assignment, the most punished confusion in the language), and both feed the same **logical operations**: Pascal's and/or/not are C++'s &&, ||, !. Same algebra, two notations — by now the course's refrain.
C++ carries an older inheritance: in a condition, **any non-zero value counts as true and 0 as false**, so an int can stand where a bool belongs — and the assignment `if (x = 5)` compiles, assigns, and reads as true, hiding a bug in plain sight. Pascal's strictness forbids the mixture: a condition must be boolean, full stop. The section's rule for the pair: write booleans as booleans in both languages; the loose reading is a trap to recognise in others' code, never a style to adopt.
