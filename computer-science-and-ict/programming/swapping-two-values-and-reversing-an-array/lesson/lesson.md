# Swapping Two Values — and Reversing an Array

## Do it first

Two glasses, one full of water, one of juice. Exchange their contents without mixing them and you will invent this lesson in your hands: you reach for a third glass. Programs swap values constantly — sorting is swapping with ambition — and they reach for the same third glass.

## Sub lesson 1 — The swap — three moves with a temporary

To **swap** the values of a and b, a third variable holds one of them safe: `temp = a; a = b; b = temp;` — **three moves**, in that order, and no other order works. The beginner's two-move version, `a = b; b = a;`, loses a's value at the first move: b's value overwrites it before it is saved, and both variables end holding b's old value. The temporary variable is the third glass — small, unglamorous, and the difference between exchange and loss. Every sort, shuffle and reversal in programming is built from this one honest move.

In your mind's eye: the swap — three moves with a temporary.

## Sub lesson 2 — Reversing an array — swaps walking to the middle

To **reverse an array** in place: swap the **first with the last**, the **second with the second-last**, walking inward until the two walkers **meet in the middle** — for an odd length, the middle element stays, already home. Five elements take two swaps; a hundred take fifty — always **half the size**, rounded down. The loop's indices are the craft: i climbs from the start while j descends from the end, and the loop stops when i is no longer less than j. Reverse is the swap's portrait as the calculator was assembly's: a tiny algorithm whose correctness can be seen whole, and whose off-by-one faults teach the array lesson's edge discipline better than any warning.

In your mind's eye: reversing an array — swaps walking to the middle.

## Say it to your companion

Tell your companion, in your own words: To **swap** the values of a and b, a third variable holds one of them safe: `temp = a; a = b; b = temp;` — **three moves**, in that order, and no other order works. The beginner's two-move version, `a = b; b = a;`, loses a's value at the first move: b's value overwrites it before it is saved, and both variables end holding b's old value. The temporary variable is the third glass — small, unglamorous, and the difference between exchange and loss. Every sort, shuffle and reversal in programming is built from this one honest move. To **reverse an array** in place: swap the **first with the last**, the **second with the second-last**, walking inward until the two walkers **meet in the middle** — for an odd length, the middle element stays, already home. Five elements take two swaps; a hundred take fifty — always **half the size**, rounded down. The loop's indices are the craft: i climbs from the start while j descends from the end, and the loop stops when i is no longer less than j. Reverse is the swap's portrait as the calculator was assembly's: a tiny algorithm whose correctness can be seen whole, and whose off-by-one faults teach the array lesson's edge discipline better than any warning. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Three. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: temp = a; a = b; b = temp;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: a's value is overwritten before it is saved. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The third glass. Do this with a real example of your own and write or say how you know it is right.
