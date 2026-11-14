# Video script — Functions in C — Library Functions and Your Own

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Library functions** are ready-made functions the language provides: **sqrt** for square roots, **pow** for powers, the string functions of the companion lesson, printf and scanf themselves. They are reached through **headers** — `#include <math.h>` borrows the mathematics toolbox as `<stdio.h>` borrowed input-output. Calling is one pattern everywhere: the function's **name**, the **arguments** in brackets, and the **returned value** used where the call stands: `area = sqrt(x);` — the call is replaced by its answer.
A **user-defined function** is written in three parts. The **prototype** — `int add(int, int);` — declares the function's name, what it takes and what it returns, so the compiler can check every call. The **definition** holds the body: the work, ending in **return**. The **call** uses it from main or anywhere, as often as needed — write once, use everywhere, fix in one place. Functions divide a program the way chapters divide a book: by their jobs — and the good-structure lesson's readability is mostly this division, done well.
