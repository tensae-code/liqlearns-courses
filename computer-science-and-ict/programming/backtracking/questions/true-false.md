# Backtracking — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: Build step by step, test each partial build, and abandon a failing one at once**
**Answer: True**

**2. (Sub lesson 1) True or false: Build step by step, test each partial build, and abandon a failing one at once** — as the answer to: What do you do when a partial build fails?
**Answer: False — Backtrack — return to the last choice point and try the next choice**

**3. (Sub lesson 1) True or false: It prunes whole branches with one early failure instead of generating every candidate whole**
**Answer: True**

**4. (Sub lesson 1) True or false: It prunes whole branches with one early failure instead of generating every candidate whole** — as the answer to: What kinds of problems yield to it?
**Answer: False — Hard placement problems — queens, routes, timetables**

**5. (Sub lesson 1) True or false: If a solution exists, the search finds it; if none does, every road is proven closed**
**Answer: True**

**6. (Sub lesson 2) True or false: If a solution exists, the search finds it; if none does, every road is proven closed** — as the answer to: What shape does a backtracking program take?
**Answer: False — A recursive procedure that places the next piece, checks conditions, and returns to step back**

**7. (Sub lesson 2) True or false: The pieces, the choices at each step, and the conditions checked**
**Answer: True**

**8. (Sub lesson 2) True or false: The pieces, the choices at each step, and the conditions checked** — as the answer to: What does returning from the recursive call do?
**Answer: False — It steps back — undoes the last placement so the next choice can be tried**

**9. (Sub lesson 2) True or false: Because the shape transfers to the next problem once it is owned**
**Answer: True**

**10. (Sub lesson 2) True or false: Because the shape transfers to the next problem once it is owned** — as the answer to: When are conditions checked?
**Answer: False — After every placement, not only at the end**
