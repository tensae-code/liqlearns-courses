# Flip-Flops — RS, JK, D and T

## Do it first

Every gate you have met is forgetful. The moment an input changes, the output is decided by the present alone; the past leaves no trace. But a computer that cannot remember even one bit cannot count, cannot store, cannot work. The way out is a beautiful trick: take two gates and wire each one's output into the other's input, in a loop. Now the circuit's output feeds back into itself, and the loop can settle into a state — and *stay* there. That state is one remembered bit. A circuit that holds one bit like this is called a flip-flop, and this lesson teaches the four kinds Montenegro's book builds from it: RS, JK, D and T.

## Sub lesson 1 — What a flip-flop is — and the RS flip-flop

A flip-flop is called **bistable**: it has exactly two stable states, and it rests in either of them until pushed. Its output is named **Q**, and it always carries a second output **Q̄**, the opposite of Q — when Q is 1, Q̄ is 0. 'Resting in a state' is the whole point: a flip-flop is the first circuit in this climb that *remembers*. It remembers exactly one bit.

The simplest member of the family is the **RS flip-flop**, named for its two inputs: **S for set** and **R for reset**. It can be built from just two NAND gates wired in a cross-coupled loop — each gate's output feeding one input of the other gate. Its behaviour has four cases, and you should be able to run them like a story. Set active (in the NAND version the inputs are active-low, pulled to 0 to act): Q becomes 1 and stays 1 — the bit is *written*. Reset active: Q becomes 0. Neither active: the flip-flop **holds** — Q keeps whatever it had, which is the memory doing its job. And the fourth case is the family's warning label: **both inputs active at once is forbidden**. It forces Q and Q̄ to the same value, breaking the rule that they are opposites, and when both inputs release together, the state the loop falls into is a coin toss — no designer may build on a coin toss.

[Picture — two NAND gates cross-coupled in a loop, outputs labelled Q and Q̄, with the four input cases listed beside it and the forbidden case crossed out]

One timing note the book is careful about: this plain RS flip-flop reacts the moment its inputs change. Real systems march in step, so most flip-flops add a **clock** — an input that says 'now' — and only change state when the clock ticks. The next part's family members are usually met in their clocked forms.

## Sub lesson 2 — JK, D and T flip-flops

Each of the other three flip-flops is the RS idea with one improvement.

The **JK flip-flop** keeps two inputs — J does set's job, K does reset's — and repairs the one flaw: when J and K are *both* active, instead of a forbidden mess the JK **toggles**: on the clock tick, Q flips to its opposite, 1 becomes 0 and 0 becomes 1. Every input combination is now legal, and the toggle behaviour turns out to be a gift — it is exactly what counters need, two lessons from now.

The **D flip-flop** is the simplest to use and the one real machines are full of. It has a single data input, **D**, and a clock. On each clock tick, Q simply *copies* D: Q next = D now. Between ticks it holds. One D flip-flop is one stored bit that can be written on command — line up eight of them and you have a byte of memory being written in one tick. When the registers lesson arrives, a register will turn out to be just a row of D flip-flops sharing one clock.

[Picture — the three flip-flops as boxes: JK with inputs J and K, D with its single input D, T with its single input T, each with a clock arrow entering from below and Q and Q̄ leaving on the right]

The **T flip-flop** also has one input, **T**. While T = 0 it holds its state; while T = 1 it toggles on every clock tick — 0, 1, 0, 1 — so its output changes at half the clock's rate: a frequency halved, a count of two. T is really a JK with J and K joined into one input, and a chain of toggling flip-flops is a counter, as the counters lesson will build.

Learn the family by their verbs: RS **sets and resets** (but never both at once), JK **sets, resets and toggles**, D **copies**, T **toggles or holds**.

## Say it to your companion

Tell your companion, in your own words: a flip-flop is two gates wired in a loop so the circuit remembers one bit, Q with its opposite Q̄; RS sets and resets but must never have both inputs active; JK fixes that case by toggling; D copies its input on each clock tick; T toggles on each tick while T is 1. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a flip-flop is — a bistable, one-bit memory with outputs Q and Q̄ — and how it differs from a gate. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: run the RS flip-flop through set, hold, reset and hold, and explain why both inputs active is forbidden. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: state what J and K do in a JK flip-flop, including the toggle that replaces the forbidden case. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: say what a D flip-flop does on a clock tick, and what a T flip-flop does while T = 1 and while T = 0. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
