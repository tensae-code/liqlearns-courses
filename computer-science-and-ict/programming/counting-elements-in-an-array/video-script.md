# Video script — Counting Elements in an Array

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The shape: **count = 0;** then for each element, **if (test) count++;**. Nothing is stored and the array is untouched — the product of the walk is the single number. The **test** is the whole art: negative (a[i] < 0), even (a[i] % 2 == 0), in a range (both bounds with &&) — write the test to match the question's exact words, edges included.
Boundary words decide counts: 'above 10' excludes 10 itself, 'at least 10' includes it — an off-by-one in the **condition**, not the loop. Some questions need **two passes**: the count of elements **above the average** cannot start until the average exists, so the program totals first, then walks again to count. Recognising a two-pass question is the section's real skill.
