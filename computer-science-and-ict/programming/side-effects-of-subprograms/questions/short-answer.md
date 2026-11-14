# Side Effects of Subprograms — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is a side effect?**
**Answer: A change a subprogram makes outside its contract — to globals, files, the screen — beyond its return and agreed parameters**

**2. (Sub lesson 1) Why is the offence subtle?**
**Answer: The heading promises a clean exchange — the extra change is invisible at the call**

**3. (Sub lesson 1) Name three seats of side effects.**
**Answer: Global variables, files, and the screen (also: devices)**

**4. (Sub lesson 1) Can two identical-looking calls differ in hidden work?**
**Answer: Yes — exactly that invisibility is the danger**

**5. (Sub lesson 1) What does the contract of a function consist of?**
**Answer: Its parameters in, its returned value out**

**6. (Sub lesson 2) What is the first move of the discipline?**
**Answer: Name it — effect-work belongs in procedures whose purpose is the effect**

**7. (Sub lesson 2) What does isolating an effect mean?**
**Answer: Passing what is needed as parameters instead of reaching for globals**

**8. (Sub lesson 2) What is required of functions?**
**Answer: To compute from parameters alone — safe to call twice, or never, inside any expression**

**9. (Sub lesson 2) Why must function calls be safe inside expressions?**
**Answer: An expression's parts may be evaluated in any order, or optimised — effects would fire unpredictably**

**10. (Sub lesson 2) What keeps programs readable, in the chapter's standard?**
**Answer: Effects staying visible at their calls**
