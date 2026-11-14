# Video script — Handling Runtime Errors

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **runtime error (σφάλμα εκτέλεσης)** is a fault that appears **while the program executes**: the data it meets breaks an operation — **division by zero**, a root of a negative number, a file that is not there, a value too large for its type. It differs from its two brothers: the **syntax error**, caught by the translator before the run, and the **logic error**, which runs quietly to a wrong answer. The runtime error **stops** the run — abnormal termination — unless the program was built expecting it.
**Handling** a runtime error means building the program's answer **before** the blow lands: **check the dangerous data first** (is the divisor zero? does the file exist? is the value in range?) and give the program an honest road when the check fails — a message that names the trouble, a fresh chance to input, a safe ending instead of a crash. The chapter's rule is a design rule: every operation that *can* break on data must be met by its check, because the run will meet every data the writer did not imagine.
