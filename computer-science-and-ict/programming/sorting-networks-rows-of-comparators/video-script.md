# Video script — Sorting Networks — Rows of Comparators

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **sorting network (réseau de tri)** is a fixed pattern of **comparators**: each comparator joins two wires and leaves the smaller value on the agreed wire (top, say). Comparators on separate wires can fire **in parallel** — a whole row at once — so a network sorts with no decisions, no memory, no control: the pattern is the program. The inquiry opens by discovering a new network: place comparators, test with shuffled inputs, watch order emerge from pure arrangement.
The inquiry's second act is sabotage: a network with a **fault (panne)** — a comparator missing, misplaced or wired wrong — fails on some inputs and passes others. Repair is methodical: find an input it fails (a counterexample), trace that input's journey wire by wire, locate the station where order was lost, and fix the pattern — then prove the repair on the cases that used to break, and their cousins. A network is ‘correct’ only when no input can embarrass it.
