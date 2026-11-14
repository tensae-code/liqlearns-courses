# Video script — Variable Scope in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A variable **assigned inside a function** is **local** to it: born when the function runs, visible only inside it, gone when it returns. That is why two functions can both use `total` in peace — each has its own. A function may **read** a name from outside (the enclosing or global scope) when it does not assign to it; the moment it **assigns**, Python treats the name as local throughout the function — the classic trap behind the vanishing change and the 'referenced before assignment' error.
Names assigned at the program's top level are **global**: visible everywhere, writable from inside a function only by declaring **`global`** — a declaration Jordan's book teaches with its warning attached: globals make programs hard to follow, because any function may change what every function sees. The craft's preference is scope's whole point: pass values **in** as parameters and **out** as returns, keep names as local as the job allows, and let the walls do their work — scope is not a nuisance but the function's privacy, and the program's sanity.
