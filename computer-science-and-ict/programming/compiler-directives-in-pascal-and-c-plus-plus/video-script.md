# Video script — Compiler Directives in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **compiler directive** is an instruction **to the compiler, not to the program**: it changes how the program is built, and itself executes nothing at run time. Pascal writes directives as special comments — **{$R+}** switches range checking on, {$R−} off; others govern overflow checks, input/output checks, debug information. The directive's home is the exact place it stands: a switch rules the text after it until switched again. Removing all directives changes no algorithm — it changes the **safety and shape of the building**.
C++ gives this work to a **preprocessor** that runs **before** compilation, driven by lines beginning with **#**: **#include** inserts a whole file's text (the libraries' headers), **#define** names a text substitution used through the program, **#ifdef / #endif** include or exclude whole parts of the text by condition. The famous first line of every C++ program, `#include <iostream>`, is a directive — the program's first word is spoken not to the machine, but to the builder about where its tools live.
