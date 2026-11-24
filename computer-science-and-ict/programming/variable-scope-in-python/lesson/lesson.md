# Variable Scope in Python

## Do it first

Two functions both use a variable called `total` — and never interfere. A third changes a variable and the change vanishes. This lesson learns the invisible walls behind both: scope.

## Sub lesson 1 — Local scope — names born inside a function

A variable **assigned inside a function** is **local** to it: born when the function runs, visible only inside it, gone when it returns. That is why two functions can both use `total` in peace — each has its own. A function may **read** a name from outside (the enclosing or global scope) when it does not assign to it; the moment it **assigns**, Python treats the name as local throughout the function — the classic trap behind the vanishing change and the 'referenced before assignment' error.

In your mind's eye: local scope. Names born inside a function.

## Sub lesson 2 — Global scope — and reaching it honestly

Names assigned at the program's top level are **global**: visible everywhere, writable from inside a function only by declaring **`global`** — a declaration Jordan's book teaches with its warning attached: globals make programs hard to follow, because any function may change what every function sees. The craft's preference is scope's whole point: pass values **in** as parameters and **out** as returns, keep names as local as the job allows, and let the walls do their work — scope is not a nuisance but the function's privacy, and the program's sanity.

In your mind's eye: global scope — and reaching it honestly.

## Say it to your companion

Tell your companion, in your own words: A variable **assigned inside a function** is **local** to it: born when the function runs, visible only inside it, gone when it returns. That is why two functions can both use `total` in peace — each has its own. A function may **read** a name from outside (the enclosing or global scope) when it does not assign to it; the moment it **assigns**, Python treats the name as local throughout the function — the classic trap behind the vanishing change and the 'referenced before assignment' error. Names assigned at the program's top level are **global**: visible everywhere, writable from inside a function only by declaring **`global`** — a declaration Jordan's book teaches with its warning attached: globals make programs hard to follow, because any function may change what every function sees. The craft's preference is scope's whole point: pass values **in** as parameters and **out** as returns, keep names as local as the job allows, and let the walls do their work — scope is not a nuisance but the function's privacy, and the program's sanity. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One assigned inside a function — visible only there, gone at return. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Each has its own local total. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: When it does not assign to it. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Makes it local throughout the function. Do this with a real example of your own and write or say how you know it is right.
