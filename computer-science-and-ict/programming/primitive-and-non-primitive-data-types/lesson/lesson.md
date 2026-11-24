# Primitive and Non-Primitive Data Types

## Do it first

Java sorts every type a variable can have into two families, and the sorting matters: it decides what a variable actually holds. Malaysia's Java chapter teaches the families together with variables and constants. In this lesson you learn the two families — and the difference in what sits in the box.

## Sub lesson 1 — Primitive types — the value itself in the box

**Primitive types** are Java's built-in simple types: byte, short, **int** and long for whole numbers; **float** and **double** for decimal numbers; **char** for a single character; **boolean** for true/false. A primitive variable holds **the value itself** — the box for int mark = 85; holds 85. Copying a primitive copies the value, so the two boxes then live independently. There are exactly eight primitives, they are written in small letters, and they cannot be broken into parts.

In your mind's eye: primitive types — the value itself in the box.

## Sub lesson 2 — Non-primitive types — a reference in the box

**Non-primitive (reference) types** — String, arrays, and every class — work differently: the variable holds a **reference**, a way to reach an **object** that lives elsewhere in memory. Copying a reference variable copies the **reference**, so both boxes reach the **same object** — change it through one and the other sees the change. Malaysia's contrast is the lesson: primitive, the value in the box; non-primitive, a pointer to the value in the box — and most beginner surprises about two variables 'changing together' are this difference, met in the wild.

In your mind's eye: non-primitive types — a reference in the box.

## Say it to your companion

Tell your companion, in your own words: **Primitive types** are Java's built-in simple types: byte, short, **int** and long for whole numbers; **float** and **double** for decimal numbers; **char** for a single character; **boolean** for true/false. A primitive variable holds **the value itself** — the box for int mark = 85; holds 85. Copying a primitive copies the value, so the two boxes then live independently. There are exactly eight primitives, they are written in small letters, and they cannot be broken into parts. **Non-primitive (reference) types** — String, arrays, and every class — work differently: the variable holds a **reference**, a way to reach an **object** that lives elsewhere in memory. Copying a reference variable copies the **reference**, so both boxes reach the **same object** — change it through one and the other sees the change. Malaysia's contrast is the lesson: primitive, the value in the box; non-primitive, a pointer to the value in the box — and most beginner surprises about two variables 'changing together' are this difference, met in the wild. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: byte, short, int, long, float, double, char, boolean. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The value itself. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The value — the two boxes then live independently. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A reference — a way to reach an object in memory. Do this with a real example of your own and write or say how you know it is right.
