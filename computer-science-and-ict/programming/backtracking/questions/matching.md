# Backtracking — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) What is backtracking's one idea?** → **Build step by step, test each partial build, and abandon a failing one at once**

**2. (Sub lesson 1) What do you do when a partial build fails?** → **Backtrack — return to the last choice point and try the next choice**

**3. (Sub lesson 1) How does backtracking improve exhaustive search?** → **It prunes whole branches with one early failure instead of generating every candidate whole**

**4. (Sub lesson 1) What kinds of problems yield to it?** → **Hard placement problems — queens, routes, timetables**

**5. (Sub lesson 1) What does 'exhaustive' still guarantee?** → **If a solution exists, the search finds it; if none does, every road is proven closed**

**6. (Sub lesson 2) What shape does a backtracking program take?** → **A recursive procedure that places the next piece, checks conditions, and returns to step back**

**7. (Sub lesson 2) What three things change from problem to problem?** → **The pieces, the choices at each step, and the conditions checked**

**8. (Sub lesson 2) What does returning from the recursive call do?** → **It steps back — undoes the last placement so the next choice can be tried**

**9. (Sub lesson 2) Why does the book drill the design twice?** → **Because the shape transfers to the next problem once it is owned**

**10. (Sub lesson 2) When are conditions checked?** → **After every placement, not only at the end**
