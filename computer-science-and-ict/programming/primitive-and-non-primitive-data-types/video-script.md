# Video script — Primitive and Non-Primitive Data Types

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Primitive types** are Java's built-in simple types: byte, short, **int** and long for whole numbers; **float** and **double** for decimal numbers; **char** for a single character; **boolean** for true/false. A primitive variable holds **the value itself** — the box for int mark = 85; holds 85. Copying a primitive copies the value, so the two boxes then live independently. There are exactly eight primitives, they are written in small letters, and they cannot be broken into parts.
**Non-primitive (reference) types** — String, arrays, and every class — work differently: the variable holds a **reference**, a way to reach an **object** that lives elsewhere in memory. Copying a reference variable copies the **reference**, so both boxes reach the **same object** — change it through one and the other sees the change. Malaysia's contrast is the lesson: primitive, the value in the box; non-primitive, a pointer to the value in the box — and most beginner surprises about two variables 'changing together' are this difference, met in the wild.
