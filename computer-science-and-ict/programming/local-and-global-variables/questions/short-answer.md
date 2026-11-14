# Local and Global Variables in Functions — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) Where is a local variable declared?**
**Answer: Inside a function**

**2. (Sub lesson 1) How long does a local variable live?**
**Answer: From the call until the return**

**3. (Sub lesson 1) Can another function see a local variable?**
**Answer: No — it is invisible outside its function**

**4. (Sub lesson 1) What does each call get?**
**Answer: Its own fresh copies of the locals**

**5. (Sub lesson 1) Why is locality a feature?**
**Answer: Functions cannot wreck each other's working values**

**6. (Sub lesson 2) Where is a global variable declared?**
**Answer: Outside all functions**

**7. (Sub lesson 2) How long does a global live?**
**Answer: For the whole run of the program**

**8. (Sub lesson 2) Who can change a global?**
**Answer: Every function**

**9. (Sub lesson 2) What is the danger of globals?**
**Answer: A change anywhere shows everywhere — bugs can come from any function**

**10. (Sub lesson 2) If a local and a global share a name, which wins inside the function?**
**Answer: The local one — the global is shadowed**

