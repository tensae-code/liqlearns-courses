# Video script — The Structure of a Pascal and C++ Program

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A Pascal program stands in fixed order: the **heading** (`program Name;`), then the **declaration part** — label, const, type, var sections, and the **subprogram declarations** (procedures and functions, each a small program in shape) — then the **main body** between begin and end. Nothing may appear out of its place: the compiler reads the program as it is built, declarations before use, always. The structure is the discipline made visible — the program as a document with a constitution and then its acts.
A C++ program is a **set of functions** with no fixed gathering: **preprocessor directives** (#include for the libraries) come first; **global declarations** and **function definitions** follow in any order the compiler can resolve; and **main** is the function where execution begins — one function among the set, marked by its name. Where Pascal is one document in fixed order, C++ is a **workshop of named tools** with main as the door. Both anatomies serve the same law: **everything used is declared, and execution starts at a known place**.
