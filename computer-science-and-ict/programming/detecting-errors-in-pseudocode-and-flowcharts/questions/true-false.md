# Detecting Errors in Pseudocode and Flowcharts — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "What does detecting errors begin with?" is: A trace — running the algorithm by hand, step by step on paper**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "What do you write during a trace?" is: A value that never changes; a step using a value before it exists (also: a path never reached)**
**Answer: False** — Every variable's value after every step

**3. (Sub lesson 1) True or false: the answer to "Name two things a trace exposes." is: A value that never changes; a step using a value before it exists (also: a path never reached)**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "In what order is the trace worked?" is: You see what you meant, not what the steps say**
**Answer: False** — In the algorithm's own order — never the order you expect

**5. (Sub lesson 1) True or false: the answer to "Why does expectation hide faults?" is: You see what you meant, not what the steps say**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "Name the loop fault a trace exposes." is: The increment or change that moves the test toward ending**
**Answer: False** — A loop with no way out — its test can never become false

**7. (Sub lesson 2) True or false: the answer to "What is missing in that loop fault, usually?" is: The increment or change that moves the test toward ending**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "Name two more common faults." is: In the algorithm — the pseudocode line or flowchart box**
**Answer: False** — A decision missing a path; steps in the wrong order (also: a wrong test, = for ≥)

**9. (Sub lesson 2) True or false: the answer to "Where is the fix made?" is: In the algorithm — the pseudocode line or flowchart box**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "After fixing, what happens to the trace?" is: A trace — running the algorithm by hand, step by step on paper**
**Answer: False** — It is re-run from the top

