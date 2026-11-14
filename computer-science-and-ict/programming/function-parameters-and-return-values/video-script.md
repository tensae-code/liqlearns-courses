# Video script — Function Parameters and Return Values

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Each **parameter** declares a **type and a name**; the call's **arguments** must match in **number, type and order**. In C++ the argument's value is **copied** into the parameter (pass by value), so changes the function makes to its parameter do not reach the caller's original variable. The parameter exists only inside the function, for the length of the call.
A function returns **at most one value**, of its declared **return type**, through **return** — which also ends the function at once, even mid-body. The caller may store the value, print it, or use it inside a bigger expression. A **void** function returns nothing and is called for what it **does**, not what it gives. The signature — return type plus parameter list — is the contract every call must honour.
