# Linear vs Pipelined Processing — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "In linear processing, when is the next instruction fetched?" is: Only after the current one is completely finished**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "Through which stages does an instruction pass?" is: One — the others wait idle**
**Answer: False** — Fetch, decode, execute

**3. (Sub lesson 1) True or false: the answer to "At any moment in linear processing, how many stages work?" is: One — the others wait idle**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "What does linear processing waste?" is: It is simple to build and easy to reason about**
**Answer: False** — The machine — two of three stages are always waiting

**5. (Sub lesson 1) True or false: the answer to "What is linear processing's virtue?" is: It is simple to build and easy to reason about**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "In pipelining, what happens at each stage at once?" is: An assembly line**
**Answer: False** — Each stage works on a different instruction — execute, decode and fetch overlap

**7. (Sub lesson 2) True or false: the answer to "Like what is pipelining pictured?" is: An assembly line**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "Once the line fills, how often does an instruction finish?" is: Throughput (instructions per time) — not the speed of a single instruction**
**Answer: False** — On every cycle

**9. (Sub lesson 2) True or false: the answer to "What does pipelining raise — and what does it not?" is: Throughput (instructions per time) — not the speed of a single instruction**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "When does the line stumble?" is: Only after the current one is completely finished**
**Answer: False** — When an instruction needs a result the line has not finished yet

