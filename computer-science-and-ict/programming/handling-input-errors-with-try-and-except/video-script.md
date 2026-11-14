# Video script — Handling Input Errors with Try and Except

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Validation** checks input **before** the program trusts it: is something there at all, is it the right **kind** (a number, where a number is needed), is it in the allowed **range**? Each failed check earns a **clear message** and another chance — 'Marks run from 0 to 100; you typed 140' teaches; a silent wrong answer corrupts. Egypt places this in the same lesson as error handling because the two are one discipline: most input errors should never become program errors at all, caught at the door by checks written from knowing exactly what the program needs.
Some errors survive validation — a conversion that fails, a file that is not there — and Python's answer is **try/except**: the risky lines go in the **try** block; if one raises an error, Python jumps to the **except** block instead of crashing, and the program responds — a message, a default, another attempt — and continues. The craft is aim: wrap the **few lines** that can fail, name the **specific** error where you can, and never let an except block swallow a fault silently, or real bugs will hide inside it. Egypt's Grade 9 book teaches this to pupils whose other error lesson is the IDLE debugger — the pair is complete: the debugger finds the program's faults; try/except survives the user's.
