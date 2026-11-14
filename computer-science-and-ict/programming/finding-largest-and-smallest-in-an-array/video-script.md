# Video script — Finding the Largest and Smallest in an Array

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Set **max = a[0]**. For each remaining element, **if (a[i] > max) max = a[i];** — after the walk, max holds the **largest value**, because every element had its chance to beat it and only a bigger one could replace it. Starting from a[0] rather than 0 is what keeps all-negative arrays honest.
**min** mirrors max with **<**. Often the **position** matters as much as the value: keep **imax** beside max, updating both together, and the program can report 'largest is 9, at index 4'. Ties keep the **first** extreme position, because the strict comparison only replaces on a true beating — a detail the exercises test.
