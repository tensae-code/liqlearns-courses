# Sorting Networks — Rows of Comparators

## Do it first

A machine with no brain: numbers enter on parallel wires, meet compare-and-swap stations in a fixed pattern, and leave sorted — every time, whatever entered. Before reading on, design the smallest such machine for three numbers.

## Sub lesson 1 — Comparators in fixed rows

A **sorting network (réseau de tri)** is a fixed pattern of **comparators**: each comparator joins two wires and leaves the smaller value on the agreed wire (top, say). Comparators on separate wires can fire **in parallel** — a whole row at once — so a network sorts with no decisions, no memory, no control: the pattern is the program. The inquiry opens by discovering a new network: place comparators, test with shuffled inputs, watch order emerge from pure arrangement.

In your mind's eye: comparators in fixed rows.

[Picture 47723 — comparators in fixed rows]

## Sub lesson 2 — Repairing a broken network

The inquiry's second act is sabotage: a network with a **fault (panne)** — a comparator missing, misplaced or wired wrong — fails on some inputs and passes others. Repair is methodical: find an input it fails (a counterexample), trace that input's journey wire by wire, locate the station where order was lost, and fix the pattern — then prove the repair on the cases that used to break, and their cousins. A network is ‘correct’ only when no input can embarrass it.

In your mind's eye: repairing a broken network.

[Picture 47724 — repairing a broken network]

## Say it to your companion

Tell your companion, in your own words: A **sorting network (réseau de tri)** is a fixed pattern of **comparators**: each comparator joins two wires and leaves the smaller value on the agreed wire (top, say). Comparators on separate wires can fire **in parallel** — a whole row at once — so a network sorts with no decisions, no memory, no control: the pattern is the program. The inquiry opens by discovering a new network: place comparators, test with shuffled inputs, watch order emerge from pure arrangement. The inquiry's second act is sabotage: a network with a **fault (panne)** — a comparator missing, misplaced or wired wrong — fails on some inputs and passes others. Repair is methodical: find an input it fails (a counterexample), trace that input's journey wire by wire, locate the station where order was lost, and fix the pattern — then prove the repair on the cases that used to break, and their cousins. A network is ‘correct’ only when no input can embarrass it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A fixed pattern of comparators that sorts any input. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Joins two wires and leaves the smaller value on the agreed wire. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Comparators on separate wires — a whole row at once. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Decisions, memory, control — the pattern is the program. Do this with a real example of your own and write or say how you know it is right.
