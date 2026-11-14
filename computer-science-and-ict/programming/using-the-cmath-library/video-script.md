# Video script — Using the cmath Library

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Library functions arrive through a **header**: `#include <cmath>` at the top makes them available. A call looks like any function call — **sqrt(81)** has the value **9** wherever it is written, so it can be stored, printed or built into a bigger expression. The functions work on decimal (double) values and return doubles.
The book's working set: **sqrt(x)** square root; **pow(x, y)** x raised to the power y; **abs / fabs** absolute value; **floor** and **ceil** rounding down and up; **round** to nearest; and the trigonometric family (sin, cos, tan — in **radians**). Using the library instead of hand-writing these is the modular habit applied: tested once by the library's makers, reused by everyone.
