# Counters — Series, Parallel and Ring — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) A 3-bit counter steps through 000, 001, 010, 011, 100, 101, 110, 111 and then returns to 000.**
**Answer: True** — Eight states = 2³, counting modulo 8, then wrapping.

**2. (Sub lesson 1) In a series counter all flip-flops change state at exactly the same moment.**
**Answer: False** — Each stage waits for the previous one's output — the change ripples, which is why it is also called asynchronous.

**3. (Sub lesson 2) A parallel counter produces the same counting sequence as a series counter of the same size.**
**Answer: True** — Both count in binary modulo 2ⁿ; they differ only in clocking — when each stage changes — not in the sequence.

**4. (Sub lesson 2) A ring counter gives more states per flip-flop than a binary counter.**
**Answer: False** — Far fewer: n states from n flip-flops, against 2ⁿ for the binary counter. Its advantage is the directly usable, decoded output.
