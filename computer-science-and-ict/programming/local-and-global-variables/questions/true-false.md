# Local and Global Variables in Functions — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "Where is a local variable declared?" is: Inside a function**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "How long does a local variable live?" is: Functions cannot wreck each other's working values**
**Answer: False** — From the call until the return

**3. (Sub lesson 1) True or false: the answer to "Can another function see a local variable?" is: No — it is invisible outside its function**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "What does each call get?" is: For the whole run of the program**
**Answer: False** — Its own fresh copies of the locals

**5. (Sub lesson 1) True or false: the answer to "Why is locality a feature?" is: Functions cannot wreck each other's working values**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "Where is a global variable declared?" is: A change anywhere shows everywhere — bugs can come from any function**
**Answer: False** — Outside all functions

**7. (Sub lesson 2) True or false: the answer to "How long does a global live?" is: For the whole run of the program**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "Who can change a global?" is: Inside a function**
**Answer: False** — Every function

**9. (Sub lesson 2) True or false: the answer to "What is the danger of globals?" is: A change anywhere shows everywhere — bugs can come from any function**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "If a local and a global share a name, which wins inside the function?" is: No — it is invisible outside its function**
**Answer: False** — The local one — the global is shadowed

