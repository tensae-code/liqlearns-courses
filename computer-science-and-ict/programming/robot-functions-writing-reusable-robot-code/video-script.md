# Video script — Robot Functions — Writing Reusable Robot Code

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **function** in the robot program is a **named block of robot code** that does one manoeuvre: **define** it once — its name and the blocks inside — then **call** it wherever the manoeuvre is needed. The book's own examples carry its names: **corner_detection**, the sensing routine that finds a corner, and **letterZ**, the driving that writes a Z. A main program made of function calls reads like the mission's plan, not its sweat.
The unit's **Smart Explorer project** is where functions earn their place: an exploring robot repeats its manoeuvres — advance, sense, turn, mark — at every new place it reaches, and a program built from named functions can be **repaired in one place** (mend corner_detection and every corner is mended) and **grown** by adding calls, not copies. Kuwait ends the unit here because this is where robot scripts become robot programs.
