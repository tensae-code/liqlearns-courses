# Linear vs Pipelined Processing — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) In linear processing, when is the next instruction fetched?**
**Answer: Only after the current one is completely finished**

**2. (Sub lesson 1) Through which stages does an instruction pass?**
**Answer: Fetch, decode, execute**

**3. (Sub lesson 1) At any moment in linear processing, how many stages work?**
**Answer: One — the others wait idle**

**4. (Sub lesson 1) What does linear processing waste?**
**Answer: The machine — two of three stages are always waiting**

**5. (Sub lesson 1) What is linear processing's virtue?**
**Answer: It is simple to build and easy to reason about**

**6. (Sub lesson 2) In pipelining, what happens at each stage at once?**
**Answer: Each stage works on a different instruction — execute, decode and fetch overlap**

**7. (Sub lesson 2) Like what is pipelining pictured?**
**Answer: An assembly line**

**8. (Sub lesson 2) Once the line fills, how often does an instruction finish?**
**Answer: On every cycle**

**9. (Sub lesson 2) What does pipelining raise — and what does it not?**
**Answer: Throughput (instructions per time) — not the speed of a single instruction**

**10. (Sub lesson 2) When does the line stumble?**
**Answer: When an instruction needs a result the line has not finished yet**

