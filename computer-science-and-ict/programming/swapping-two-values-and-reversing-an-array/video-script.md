# Video script — Swapping Two Values — and Reversing an Array

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

To **swap** the values of a and b, a third variable holds one of them safe: `temp = a; a = b; b = temp;` — **three moves**, in that order, and no other order works. The beginner's two-move version, `a = b; b = a;`, loses a's value at the first move: b's value overwrites it before it is saved, and both variables end holding b's old value. The temporary variable is the third glass — small, unglamorous, and the difference between exchange and loss. Every sort, shuffle and reversal in programming is built from this one honest move.
To **reverse an array** in place: swap the **first with the last**, the **second with the second-last**, walking inward until the two walkers **meet in the middle** — for an odd length, the middle element stays, already home. Five elements take two swaps; a hundred take fifty — always **half the size**, rounded down. The loop's indices are the craft: i climbs from the start while j descends from the end, and the loop stops when i is no longer less than j. Reverse is the swap's portrait as the calculator was assembly's: a tiny algorithm whose correctness can be seen whole, and whose off-by-one faults teach the array lesson's edge discipline better than any warning.
