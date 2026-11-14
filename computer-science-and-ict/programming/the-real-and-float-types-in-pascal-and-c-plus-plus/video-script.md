# Video script — The Real and float Types in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A real value is stored in two parts: the **mantissa** — the value's significant digits — and the **exponent** — the power of two (or ten, in the written E form) that places the point. Pascal's **real** and C++'s **float** are the school sizes; C++ adds **double**, with roughly twice the mantissa bits — **double precision**. More mantissa bits mean **more exact digits**; more exponent range means larger and smaller magnitudes. No size escapes the principle: between any two stored neighbours, infinitely many true values share the same stored one.
Because storage is approximate, the pair shares its commandments. **Never test reals for exact equality** — test that their difference is small. **Expect accumulation**: many small additions drift. **Format your output**: digits beyond the type's precision are noise the type never stored. And choose float against double by the data: measurements with five honest digits gain nothing from double's fifteen, while money and long computations argue for the wider mantissa. Grade 12's error chapters are this section, grown up.
