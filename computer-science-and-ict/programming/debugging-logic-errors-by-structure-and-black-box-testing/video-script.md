# Video script — Debugging Logic Errors by Structure — and Black-Box Testing

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The unit sorts the hunt by the structure under suspicion. In **selection**: the condition's edges (what happens *at* the boundary value?) and the branch that was never taken in testing. In **repetition**: the loop that runs once too few or too many, and the variable never updated inside it. In **arrays**: the index that steps one place too far, the loop bound that skips the last place. In **subprograms**: the parameter passed in the wrong order, the local name shadowing the caller's. Each structure has its own favourite hiding places, and the debugger checks them in that structure's order.
**Black-box testing (μαύρο κουτί)** tests the program **from its statement alone**: the tester chooses inputs — typical, boundary and hostile — computes the **expected** answers by hand from what the program *should* do, runs it, and compares, never reading the code and so never excused by it. A mismatch convicts the program, not the test. Beside the error-kind teaching of the same unit (syntactic errors, abnormal-termination errors, logic errors), black-box testing is the standing method: it finds logic errors precisely because it refuses to be told where to look kindly.
