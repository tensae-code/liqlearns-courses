# Detecting Errors in Pseudocode and Flowcharts — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does detecting errors begin with?**
**Answer: A trace — running the algorithm by hand, step by step on paper**

**2. (Sub lesson 1) What do you write during a trace?**
**Answer: Every variable's value after every step**

**3. (Sub lesson 1) Name two things a trace exposes.**
**Answer: A value that never changes; a step using a value before it exists (also: a path never reached)**

**4. (Sub lesson 1) In what order is the trace worked?**
**Answer: In the algorithm's own order — never the order you expect**

**5. (Sub lesson 1) Why does expectation hide faults?**
**Answer: You see what you meant, not what the steps say**

**6. (Sub lesson 2) Name the loop fault a trace exposes.**
**Answer: A loop with no way out — its test can never become false**

**7. (Sub lesson 2) What is missing in that loop fault, usually?**
**Answer: The increment or change that moves the test toward ending**

**8. (Sub lesson 2) Name two more common faults.**
**Answer: A decision missing a path; steps in the wrong order (also: a wrong test, = for ≥)**

**9. (Sub lesson 2) Where is the fix made?**
**Answer: In the algorithm — the pseudocode line or flowchart box**

**10. (Sub lesson 2) After fixing, what happens to the trace?**
**Answer: It is re-run from the top**

