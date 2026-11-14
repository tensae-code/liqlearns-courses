# Function Parameters and Return Values

## Do it first

A function is a machine with an in-tray and an out-tray. This lesson is about exactly what goes in, and the one thing that comes out.

## Sub lesson 1 — Parameters — inputs by copy

Each **parameter** declares a **type and a name**; the call's **arguments** must match in **number, type and order**. In C++ the argument's value is **copied** into the parameter (pass by value), so changes the function makes to its parameter do not reach the caller's original variable. The parameter exists only inside the function, for the length of the call.

[Picture — parameters — inputs by copy]

## Sub lesson 2 — The return value — one output

A function returns **at most one value**, of its declared **return type**, through **return** — which also ends the function at once, even mid-body. The caller may store the value, print it, or use it inside a bigger expression. A **void** function returns nothing and is called for what it **does**, not what it gives. The signature — return type plus parameter list — is the contract every call must honour.

[Picture — the return value — one output]

## Say it to your companion

Tell your companion, in your own words: Parameters are a function's input slots — each call copies its arguments into them — and the return value is the function's single output handed back to the caller; together they are the function's contract: what must be given, in what types and order, and what comes back. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The parameters in number, type and order. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No — the function works on a copy. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: At most one. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Store it and print it (using it in an expression also counts). Do this with a real example of your own and write or say how you know it is right.
