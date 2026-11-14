# Simple Data Types and Their Ranges

## Do it first

Every value in a program wears a type — and every type has edges. This lesson learns the simple types and where their edges are.

## Sub lesson 1 — The simple types — one value, one kind

A **simple (scalar) type** holds one value of one kind. The working family: **integer** (whole numbers), **real/floating** (numbers with a fraction), **character** (one symbol) and **string** (text), **Boolean/logical** (true or false), and in C++ the smaller and larger cousins — `short`, `long`, `float`, `double` — that trade range for memory. Armenia's Grade 10 book builds its 'Types. Composite structures' theme on them (Lesson 17): simple types first, then the composite types (array and structure) built from them.

[Picture — The simple types — one value, one kind]

## Sub lesson 2 — Ranges — the edges of a type, and overflow

A type stored in a fixed number of bits has a **range**: the smallest and largest values it can hold. An 8-bit signed integer holds −128…127; add 1 to 127 and it **overflows** — wrapping to −128 or behaving wrongly, silently. Reals trade differently: a huge range, but **limited precision** — digits beyond the type's count are rounded away. Choosing a type is therefore an engineering decision: big enough for the honest largest value (with room to spare), small enough not to waste memory, and its edges written into the program's tests.

[Picture — Ranges — the edges of a type, and overflow]

## Say it to your companion

Tell your companion, in your own words: A **simple (scalar) type** holds one value of one kind. The working family: **integer** (whole numbers), **real/floating** (numbers with a fraction), **character** (one symbol) and **string** (text), **Boolean/logical** (true or false), and in C++ the smaller and larger cousins — `short`, `long`, `float`, `double` — that trade range for memory. Armenia's Grade 10 book builds its 'Types. Composite structures' theme on them (Lesson 17): simple types first, then the composite types (array and structure) built from them. A type stored in a fixed number of bits has a **range**: the smallest and largest values it can hold. An 8-bit signed integer holds −128…127; add 1 to 127 and it **overflows** — wrapping to −128 or behaving wrongly, silently. Reals trade differently: a huge range, but **limited precision** — digits beyond the type's count are rounded away. Choosing a type is therefore an engineering decision: big enough for the honest largest value (with room to spare), small enough not to waste memory, and its edges written into the program's tests. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One value of one kind Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Integer, real/floating, character/string, and Boolean/logical Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Range and precision against memory — smaller types hold less, larger types hold more Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Boolean (logical) — true and false Do this with a real example of your own and write or say how you know it is right.
