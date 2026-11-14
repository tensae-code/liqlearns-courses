# Side Effects of Subprograms — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) What is a side effect?** → **A change a subprogram makes outside its contract — to globals, files, the screen — beyond its return and agreed parameters**

**2. (Sub lesson 1) Why is the offence subtle?** → **The heading promises a clean exchange — the extra change is invisible at the call**

**3. (Sub lesson 1) Name three seats of side effects.** → **Global variables, files, and the screen (also: devices)**

**4. (Sub lesson 1) Can two identical-looking calls differ in hidden work?** → **Yes — exactly that invisibility is the danger**

**5. (Sub lesson 1) What does the contract of a function consist of?** → **Its parameters in, its returned value out**

**6. (Sub lesson 2) What is the first move of the discipline?** → **Name it — effect-work belongs in procedures whose purpose is the effect**

**7. (Sub lesson 2) What does isolating an effect mean?** → **Passing what is needed as parameters instead of reaching for globals**

**8. (Sub lesson 2) What is required of functions?** → **To compute from parameters alone — safe to call twice, or never, inside any expression**

**9. (Sub lesson 2) Why must function calls be safe inside expressions?** → **An expression's parts may be evaluated in any order, or optimised — effects would fire unpredictably**

**10. (Sub lesson 2) What keeps programs readable, in the chapter's standard?** → **Effects staying visible at their calls**
