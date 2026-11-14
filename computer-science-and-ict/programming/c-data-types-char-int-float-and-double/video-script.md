# Video script — C Data Types — char, int, float and double

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **char** type holds **one character** — one byte — stored as its code number (the character-codes lesson): 'A' is kept as 65. The **int** type holds **whole numbers** — counts, ages, marks — in (commonly) four bytes, with a range in the billions either side of zero; a decimal put into an int is **cut, not rounded** — 3.9 becomes 3 — which is either the programmer's intention or their quietest bug. Variables are declared with their type before use: `int marks; char grade;` — C checks types as it compiles, and its complaints are the type system standing guard.
Decimals live in **float** (single precision, four bytes, about seven trustworthy digits) and **double** (double precision, eight bytes, about fifteen) — the money, measurements and science types, chosen by how much exactness the work deserves. Each type has its **format specifier** for printf and scanf: **%d** for int, **%c** for char, **%f** for float and double in printing — the specifier is the promise the programmer makes about what is coming, and a lying specifier prints garbage from honest data. Type, declaration, specifier: the three agreements this lesson binds together.
