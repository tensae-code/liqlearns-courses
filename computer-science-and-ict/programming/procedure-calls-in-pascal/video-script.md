# Video script — Procedure Calls in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **procedure call** is an instruction written as the procedure's **name followed by its actual parameters in brackets**: `PrintRow(i, total);`. Executing the call means: the actual parameters' values are handed to the procedure, its body runs as a composed action, and control **returns to the instruction after the call**. Standard procedures are called the same way — `writeln(x)` is a call to the built-in writing procedure. A call is one instruction in the calling program, however many instructions the called body holds.
The call is the hinge of structured programming. Work **written once** as a procedure can be **called from many places** — with different actual parameters each time, so one body serves many data. The main program becomes a readable plan of named deeds: read, compute, print — each name a call. And a fault inside a procedure is fixed **once**, in its body, repairing every call at a stroke. Grade 12 will build the full subprogram theory on this Grade 8 instruction.
